# Flow artificial chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.4.3; first proposed by Kreyssig & Dittrich, 2011.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/flow-ac", seed=0)   # same as "flow-ac"
print(net.summary())
```
