# Polymers as Turing machines / pattern processing chemistry

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §10.5.3; first proposed by McCaskill, 1988; hardware realisations NGEN/POLYP with Tangen, Schulte, Maeke, Gemm, Breyer, Ackermann.

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/mccaskill-polymer-tm", seed=0)   # same as "mccaskill-polymer-tm"
print(net.summary())
```
