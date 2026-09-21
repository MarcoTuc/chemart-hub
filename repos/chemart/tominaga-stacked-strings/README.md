# Tominaga's stackable-string chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §18.3.2; first proposed by Tominaga et al., 2004-2009.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/tominaga-stacked-strings", seed=0)   # same as "tominaga-stacked-strings"
print(net.summary())
```
