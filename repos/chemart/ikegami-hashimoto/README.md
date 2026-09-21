# Machine-tape chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §10.5.4; first proposed by Ikegami & Hashimoto, 1995.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/ikegami-hashimoto", seed=0)   # same as "ikegami-hashimoto"
print(net.summary())
```
