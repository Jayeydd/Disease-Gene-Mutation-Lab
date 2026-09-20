# Results Summary

## Part XI — Artificial Mutation Experiment
Choice made: One‑nucleotide deletion at position c.100

### Prediction
Removing one base at c.100 would shift the reading frame starting from that point. Every codon after it would be read incorrectly, so the amino acid sequence would change completely. I expected a much shorter protein with an early stop codon.

### What Actually Happened
| Detail | Result |
|---|---|
| Deletion position | c.100 |
| Base removed | Guanine (G) |
| CDS length | 8,615 bp — 1 base shorter |
| Protein length | 34 amino acids |
| Frame shift start | After amino acid 33 |
| Premature stop | Codon 34 |
| Sequence match | First 33 same as wild‑type; all after position 33 different or missing |


---

## Part XII — Compare All Three Sequences

| Feature | Wild‑Type | Documented Mutation<br>c.8326C>T | Artificial Mutation<br>c.100delG |
|---|---|---|---|
| CDS length | 8,616 bp | 8,616 bp - no change | 8,615 bp - minus 1 bp |
| Protein length | 2,871 amino acids | 2,775 amino acids - lost 96 at end | 34 amino acids |
| Mutation type | — | Nonsense substitution | Frameshift deletion |
| Reading frame | — | Unchanged  | Shifted from codon 34 onward  |
| Early stop? | No | Yes - position 2,776 | Yes - position 34 |
| Amino acids changed | — | Only last 96 | Almost entire protein after position 33 |
| Function | Fully works | Shortened; causes Marfan syndrome | Non‑functional; degraded |

### How & Why They Differ
Both mutations result in shorter, non‑functional protein, but in very different ways. The documented change just replaces one base, keeps the reading frame intact, and only cuts off the very end so 2,775 amino acids still form normally. The one‑base deletion near the start shifts the frame completely, scrambling everything after position 33 and stopping at only 34 amino acids. This shows that **where** a mutation happens and **what kind** it is directly control how much damage occurs, a frameshift early in the sequence is far more destructive.

---

## Summary
- Not all mutations alter protein length the same way
- Preserved reading frame = most sequence stays normal
- Frameshift = widespread damage and early stop
- Location matters greatly — earlier mutations affect more of the protein
