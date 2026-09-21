# ARMS (Abstract Rewriting System on Multisets)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.4; ecology application 8.2.3; p53 model 18.3.2; first proposed by Suzuki & Tanaka, 1997.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/arms", seed=0)   # same as "arms"
print(net.summary())
```
