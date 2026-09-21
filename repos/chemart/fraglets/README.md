# Fraglets

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §16.2.1, 17.3.1; appendix (Fraglets.py, NetFraglets.py); first proposed by Tschudin, 2003.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/fraglets", seed=0)   # same as "fraglets"
print(net.summary())
```
