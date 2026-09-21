# RAF sets (reflexively autocatalytic, F-generated)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §6.3.1; first proposed by Hordijk & Steel, 2004-2015.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/raf", seed=0)   # same as "raf"
print(net.summary())
```
