# Bondable Cellular Automata (BCA)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §10.7.3; first proposed by Hatcher, Banzhaf & Yu, 2011.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/bondable-ca", seed=0)   # same as "bondable-ca"
print(net.summary())
```
