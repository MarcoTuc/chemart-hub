# Automata reaction (32-bit binary string chemistry)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §10.6.1; first proposed by Dittrich & Banzhaf, 1998.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/automata-reaction", seed=0)   # same as "automata-reaction"
print(net.summary())
```
