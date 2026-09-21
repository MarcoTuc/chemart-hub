# Varela-Maturana-Uribe autopoiesis model

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §6.1.5; first proposed by Varela, Maturana & Uribe, 1974.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/autopoiesis-vmu", seed=0)   # same as "autopoiesis-vmu"
print(net.summary())
```
