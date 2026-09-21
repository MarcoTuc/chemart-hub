# RNA-folding ribozyme artificial chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §18.1.1; first proposed by Ullrich & Flamm, 2008.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/rna-folding-ac", seed=0)   # same as "rna-folding-ac"
print(net.summary())
```
