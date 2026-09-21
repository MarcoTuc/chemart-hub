# Laing's artificial molecular machines

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §10.5.1; first proposed by Laing, 1972-1977.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/laing-molecular-machines", seed=0)   # same as "laing-molecular-machines"
print(net.summary())
```
