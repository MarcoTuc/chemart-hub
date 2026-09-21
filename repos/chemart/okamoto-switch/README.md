# Okamoto's biochemical switch

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §17.4.1; first proposed by Okamoto, Sakai & Hayashi, 1987-1993.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/okamoto-switch", seed=0)   # same as "okamoto-switch"
print(net.summary())
```
