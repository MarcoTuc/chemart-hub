# Algorithmic chemistry for music composition

One of the artificial chemistries of Banzhaf & Yamamoto, *Artificial Chemistries* (MIT Press, 2015), §16.4; first proposed by Miura & Tominaga, 2006 (homophonic); Tominaga & Setomoto, 2008 (polyphonic).

Its generator ships with the `chemart` library, so loading it runs no code from the hub and needs no `trust_remote_code`.

```python
import chemart

net = chemart.generate_network("chemart/music-ac", seed=0)   # same as "music-ac"
print(net.summary())
```
