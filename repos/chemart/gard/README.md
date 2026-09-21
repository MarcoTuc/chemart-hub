# GARD (Graded Autocatalysis Replication Domain)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §6.2.4; first proposed by Segre, Lancet et al., 1998-2001.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/gard", seed=0)   # same as "gard"
print(net.summary())
```
