# Conrad's lock-and-key enzymatic / self-assembly processor

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §11.2.1; also 17.1.2 (emergence vs. programmability tradeoff); first proposed by Conrad, 1985-1992; wet realisation by Zauner & Conrad, 2001.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/conrad-enzymatic", seed=0)   # same as "conrad-enzymatic"
print(net.summary())
```
