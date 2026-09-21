# Network Artificial Chemistry (NAC)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.3.3; folding 18.1.1; first proposed by Suzuki, 2004-2009.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/nac", seed=0)   # same as "nac"
print(net.summary())
```
