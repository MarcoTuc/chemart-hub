# Mechanical self-assembly (Hosokawa)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §20.1; first proposed by Hosokawa, Shimoyama & Miura, 1994.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/mechanical-self-assembly", seed=0)   # same as "mechanical-self-assembly"
print(net.summary())
```
