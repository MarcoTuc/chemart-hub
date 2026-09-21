# Chemical Abstract Machine (CHAM)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.3; first proposed by Berry & Boudol, 1990.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/cham", seed=0)   # same as "cham"
print(net.summary())
```
