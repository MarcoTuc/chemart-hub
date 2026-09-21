# Kappa calculus

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.7; first proposed by Danos & Laneve, 2004; the Kappa language: Danos, Feret, Fontana, Harmer, Krivine et al., 2007 onwards.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/kappa-calculus", seed=0)   # same as "kappa-calculus"
print(net.summary())
```
