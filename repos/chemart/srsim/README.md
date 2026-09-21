# SRSim (rule-based spatial simulator)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §18.3.3; first proposed by Gruenert & Dittrich, 2010-2013.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/srsim", seed=0)   # same as "srsim"
print(net.summary())
```
