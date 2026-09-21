# DNA automaton (Benenson-Shapiro)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §19.3.1; first proposed by Shapiro 1998-1999 (blueprint); Benenson, Paz-Elizur, Adar, Keinan, Livneh & Shapiro 2001 (first automaton); Benenson, Adar, Paz-Elizur, Livneh & Shapiro 2003 (the ATP-free automaton implemented here).

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/dna-automaton", seed=0)   # same as "dna-automaton"
print(net.summary())
```
