# Embedded particles in cellular automata

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §10.7.2; first proposed by Hanson & Crutchfield 1992; Crutchfield & Mitchell 1995; Hordijk, Crutchfield & Mitchell 1996-1998.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/ca-embedded-particles", seed=0)   # same as "ca-embedded-particles"
print(net.summary())
```
