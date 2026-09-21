# Conservative random chemical reaction networks

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.3.2; first proposed by Bigan, Steyaert & Douady, 2013.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/bigan-conservative-crn", seed=0)   # same as "bigan-conservative-crn"
print(net.summary())
```
