# Bagley & Farmer autocatalytic metabolism

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §6.3.1, 7.3.1; first proposed by Bagley & Farmer, 1992; Bagley, Farmer & Fontana, 1992.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/bagley-farmer", seed=0)   # same as "bagley-farmer"
print(net.summary())
```
