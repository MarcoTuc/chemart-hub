# Self-replicating loops in cellular automata

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §10.4, 10.7.2; ecology 8.2.3; first proposed by von Neumann 1966; Langton 1984; Byl 1989; Reggia 1993; Sayama 1998-2004.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/sr-loops", seed=0)   # same as "sr-loops"
print(net.summary())
```
