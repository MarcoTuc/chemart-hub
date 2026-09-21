# Molecular Traveling Salesman

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §17.2.1; first proposed by Banzhaf, 1990.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/molecular-tsp", seed=0)   # same as "molecular-tsp"
print(net.summary())
```
