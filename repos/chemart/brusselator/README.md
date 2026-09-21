# Brusselator

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §17.4.2, 19.3; ARMS 9.4; first proposed by Prigogine & Lefever, 1968.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/brusselator", seed=0)   # same as "brusselator"
print(net.summary())
```
