# Chemoton

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §6.1.4; wet computing 17.4.1; first proposed by Ganti, ~1952/1971.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/chemoton", seed=0)   # same as "chemoton"
print(net.summary())
```
