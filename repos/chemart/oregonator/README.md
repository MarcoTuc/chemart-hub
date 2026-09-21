# Oregonator (Belousov-Zhabotinsky)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §19.3.3; first proposed by Field & Noyes, 1974.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/oregonator", seed=0)   # same as "oregonator"
print(net.summary())
```
