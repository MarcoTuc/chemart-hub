# String Metabolic Network (SMN)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §18.3.1; first proposed by Ono, Fujiwara & Yuta, 2005.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/smn", seed=0)   # same as "smn"
print(net.summary())
```
