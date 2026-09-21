# Random catalytic reaction networks

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §7.2.9; first proposed by Stadler, Fontana & Miller, 1993.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/random-catalytic-networks", seed=0)   # same as "random-catalytic-networks"
print(net.summary())
```
