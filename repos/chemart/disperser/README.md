# Chemical disperser (load balancing)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §17.3.1; appendix (Disperser.py); first proposed by Meyer & Tschudin, 2009.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/disperser", seed=0)   # same as "disperser"
print(net.summary())
```
