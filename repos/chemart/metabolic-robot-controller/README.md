# Metabolic / artificial biochemical network robot controllers

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §16.1.3; first proposed by Ziegler & Banzhaf, 2001; Lones, Fuente, Turner et al..

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/metabolic-robot-controller", seed=0)   # same as "metabolic-robot-controller"
print(net.summary())
```
