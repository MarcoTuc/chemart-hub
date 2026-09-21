# P systems (membrane computing)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.5; multicompartment SSA 4.3; biology 18.3.2; first proposed by Paun, 1998.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/p-systems", seed=0)   # same as "p-systems"
print(net.summary())
```
