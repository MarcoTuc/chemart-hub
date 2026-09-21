# Stringmol

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.1.2; first proposed by Hickinbotham, Clark, Stepney et al. (University of York), 2009-2011.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/stringmol", seed=0)   # same as "stringmol"
print(net.summary())
```
