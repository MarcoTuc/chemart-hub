# AlChemy (lambda-calculus chemistry)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.1; first proposed by Fontana, 1991; Fontana & Buss, 1994.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/alchemy", seed=0)   # same as "alchemy"
print(net.summary())
```
