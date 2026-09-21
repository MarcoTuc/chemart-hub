# Prime number (number-division) chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §1 (eqs. 1.4-1.5), 2.5.2, appendix (NumberChem.py, NumberChemHO divrule); first proposed by Banzhaf, Dittrich & Rauhe, 1996.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/prime-number-chemistry", seed=0)   # same as "prime-number-chemistry"
print(net.summary())
```
