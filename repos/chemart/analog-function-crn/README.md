# Analog computation of algebraic functions with concentrations

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §17.4.3; first proposed by Hjelmfelt et al.; Deckard & Sauro; Dittrich et al..

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/analog-function-crn", seed=0)   # same as "analog-function-crn"
print(net.summary())
```
