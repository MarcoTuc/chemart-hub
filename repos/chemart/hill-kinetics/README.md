# Hill kinetics (cooperative binding)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §18.2.2; used by the Repressilator 19.3.2.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/hill-kinetics", seed=0)   # same as "hill-kinetics"
print(net.summary())
```
