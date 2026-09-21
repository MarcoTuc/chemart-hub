# Adleman's DNA Hamiltonian Path computation

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §19.3.1; first proposed by Adleman, 1994.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/dna-hpp", seed=0)   # same as "dna-hpp"
print(net.summary())
```
