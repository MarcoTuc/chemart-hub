# Bitstring immune system model (idiotypic network)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.2.2; first proposed by Farmer, Packard & Perelson, 1986.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/farmer-immune", seed=0)   # same as "farmer-immune"
print(net.summary())
```
