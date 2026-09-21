# Ono & Ikegami autopoietic protocells

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §6.3.2; first proposed by Ono & Ikegami, 1999-2003.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/ono-ikegami-protocell", seed=0)   # same as "ono-ikegami-protocell"
print(net.summary())
```
