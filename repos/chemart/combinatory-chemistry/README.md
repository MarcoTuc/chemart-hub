# Combinatory Chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §-; first proposed by Kruszewski & Mikolov, 2020.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/combinatory-chemistry", seed=0)   # same as "combinatory-chemistry"
print(net.summary())
```
