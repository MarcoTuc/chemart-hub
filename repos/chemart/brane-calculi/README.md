# Brane calculi

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.7; first proposed by Cardelli, 2004.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/brane-calculi", seed=0)   # same as "brane-calculi"
print(net.summary())
```
