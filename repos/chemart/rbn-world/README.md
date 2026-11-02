# RBN World

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §18.4.2; subsymbolic AC 10.7.3; first proposed by Faulconbridge, Stepney, Miller & Caves, 2009-2011.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/rbn-world", seed=0)   # same as "rbn-world"
print(net.summary())
```
