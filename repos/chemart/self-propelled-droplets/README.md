# Self-propelled oil droplets

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §19.2.5; first proposed by Hanczyc et al., 2007-2011.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/self-propelled-droplets", seed=0)   # same as "self-propelled-droplets"
print(net.summary())
```
