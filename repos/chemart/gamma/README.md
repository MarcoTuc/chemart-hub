# Gamma / gamma-calculus

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.2; first proposed by Banatre & Le Metayer, 1986 (INRIA RR-566), 1990, 1993; gamma-calculus: Banatre, Fradet & Radenac, 2004.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/gamma", seed=0)   # same as "gamma"
print(net.summary())
```
