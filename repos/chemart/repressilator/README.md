# Repressilator

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §19.3.2; appendix (Repressilator.py); first proposed by Elowitz & Leibler, 2000.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/repressilator", seed=0)   # same as "repressilator"
print(net.summary())
```
