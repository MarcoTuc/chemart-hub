# Molecular Classifier System (MCS.bl)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.1.1; first proposed by Decraene, Mitchell & McMullin, 2006-2011; based on Holland's Broadcast Language (1975) and classifier systems.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/mcs-bl", seed=0)   # same as "mcs-bl"
print(net.summary())
```
