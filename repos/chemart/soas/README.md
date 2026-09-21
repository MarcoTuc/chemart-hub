# Self-Organizing Assembly Systems (SOAS)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §20.1; first proposed by Frei, Di Marzo Serugendo & Serbanuta, 2010-2012.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/soas", seed=0)   # same as "soas"
print(net.summary())
```
