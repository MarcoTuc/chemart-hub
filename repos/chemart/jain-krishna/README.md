# Jain-Krishna autocatalytic set model

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §15.2.2, 15.2.3; first proposed by Jain & Krishna, 1998-2002.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/jain-krishna", seed=0)   # same as "jain-krishna"
print(net.summary())
```
