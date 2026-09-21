# Chemical Casting Model (CCM)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §17.2.2; first proposed by Kanada, 1992-1996.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/ccm", seed=0)   # same as "ccm"
print(net.summary())
```
