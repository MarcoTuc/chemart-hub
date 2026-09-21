# Colored chameleon chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §2.5.1; first proposed by Winkler, 2009 puzzle (Communications of the ACM); formulated as an AC by Banzhaf & Yamamoto.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/chameleon", seed=0)   # same as "chameleon"
print(net.summary())
```
