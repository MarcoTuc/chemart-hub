# ToyChem (graph-based toy model of chemistry)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.3.1; used in the RNA AC of 18.1.1; first proposed by Benko, Flamm & Stadler, 2003-2006.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/toychem", seed=0)   # same as "toychem"
print(net.summary())
```
