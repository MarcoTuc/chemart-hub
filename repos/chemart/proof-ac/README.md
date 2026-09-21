# Artificial chemistry as a proof search system

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §16.5; first proposed by Busch & Banzhaf, 2003; Busch, 2004 (idea: Fontana & Buss, 1996).

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/proof-ac", seed=0)   # same as "proof-ac"
print(net.summary())
```
