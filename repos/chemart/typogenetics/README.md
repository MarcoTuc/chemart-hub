# Typogenetics

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §10.5.2; lock-and-key 11.2; first proposed by Hofstadter, 1979; Morris, 1989; Varetto, 1993.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/typogenetics", seed=0)   # same as "typogenetics"
print(net.summary())
```
