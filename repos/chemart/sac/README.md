# SAC (string-based artificial chemistry with cells)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.1.3; first proposed by Suzuki & Ono, 2002-2003.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/sac", seed=0)   # same as "sac"
print(net.summary())
```
