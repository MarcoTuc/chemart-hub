# Dorin & Korb virtual ecosystem chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §8.2.3; first proposed by Dorin & Korb, 2007.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/dorin-korb-ecosystem", seed=0)   # same as "dorin-korb-ecosystem"
print(net.summary())
```
