# Kauffman autocatalytic sets (binary polymer model)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §6.3.1; first proposed by Kauffman, 1986; Farmer, Kauffman & Packard, 1986.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/kauffman-autocatalytic-sets", seed=0)   # same as "kauffman-autocatalytic-sets"
print(net.summary())
```
