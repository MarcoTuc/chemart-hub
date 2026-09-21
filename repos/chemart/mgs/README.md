# MGS

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.6; biology 18.3.2; first proposed by Giavitto & Michel, 2001.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/mgs", seed=0)   # same as "mgs"
print(net.summary())
```
