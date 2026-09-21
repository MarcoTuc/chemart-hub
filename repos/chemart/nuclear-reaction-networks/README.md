# Nuclear reaction networks

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §20.2.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/nuclear-reaction-networks", seed=0)   # same as "nuclear-reaction-networks"
print(net.summary())
```
