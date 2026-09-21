# Matrix chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §chapter 3; revisited in 12.5.2, 13.2; first proposed by Banzhaf, 1993.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/matrix-chemistry", seed=0)   # same as "matrix-chemistry"
print(net.summary())
```
