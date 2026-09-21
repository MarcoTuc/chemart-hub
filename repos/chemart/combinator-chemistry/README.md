# Combinator chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.8; 7.3.1 (multiset products, organisations); 12.1 (variable population); first proposed by Speroni di Fenizio, 2000.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/combinator-chemistry", seed=0)   # same as "combinator-chemistry"
print(net.summary())
```
