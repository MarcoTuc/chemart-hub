# Random Boolean Networks (RBN) and RBN World

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §18.4.2; subsymbolic AC 10.7.3; first proposed by Kauffman, 1969; RBN World: Faulconbridge, Stepney, Miller & Caves, 2009-2011.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/rbn", seed=0)   # same as "rbn"
print(net.summary())
```
