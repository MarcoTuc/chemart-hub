# L-systems

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §9.8; first proposed by Lindenmayer, 1968; Prusinkiewicz & Lindenmayer, 1990.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/l-systems", seed=0)   # same as "l-systems"
print(net.summary())
```
