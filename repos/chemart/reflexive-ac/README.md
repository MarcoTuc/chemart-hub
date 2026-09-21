# Reflexive artificial chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.8; first proposed by Salzberg, 2007.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/reflexive-ac", seed=0)   # same as "reflexive-ac"
print(net.summary())
```
