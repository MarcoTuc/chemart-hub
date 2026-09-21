# High-order chemistry (rules as molecules)

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §appendix: Writing Your Own Artificial Chemistry in Python, 'A High-Order Chemistry' (figure 3, divrule); module list (HighOrderChem.py); first proposed by Yamamoto, 2014 (PyCellChemistry); Banzhaf & Yamamoto, 2015.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/high-order-chem", seed=0)   # same as "high-order-chem"
print(net.summary())
```
