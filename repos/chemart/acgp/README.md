# Algorithmic Chemistry GP (ACGP)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §16.6; first proposed by Banzhaf & Lasarczyk, 2004-2007.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/acgp", seed=0)   # same as "acgp"
print(net.summary())
```
