# Michaelis-Menten enzyme kinetics

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §18.2.1; also 4.4 (as an abridgement method).

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/michaelis-menten", seed=0)   # same as "michaelis-menten"
print(net.summary())
```
