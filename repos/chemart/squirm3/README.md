# Squirm3

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.4.1; first proposed by Hutton, 2002-2007.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/squirm3", seed=0)   # same as "squirm3"
print(net.summary())
```
