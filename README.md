# Unbounded coefficient oscillation after unit translation

Aurantium · v0.1.0 · 14 October 2026

This short note gives an explicit recursive family of polynomials with positive nonincreasing integer coefficients. After the fixed translation x → x+1, the coefficient lists have arbitrarily many sign changes in their adjacent differences, with zero differences deleted. The degree at step r is 8·2^r−5 and the number of changes is at least 2r+1.

- [Complete four-page proof](paper/proof.pdf)
- [Standalone LaTeX source](paper/proof.tex)
- [References and their roles](REFERENCES.md)
- [Attribution and rights](RIGHTS.md)

The proof includes the finite binomial identity, integer perturbation bound, precise positions of the two new signs, the alternating-subsequence argument and the quantified conclusion. It uses no numerical experiment or external mathematical theorem beyond elementary finite identities. No code or new computational result is included.

The input monotonicity is weak and allows an endpoint mode. The result concerns the fixed shift 1 and a lower bound on oscillation; it does not claim an exact count, a minimum degree or a simultaneous statement for every positive shift.

A public transcription of the 2000 Alvarez–Amadis–Rosales report contains the related oscillation question and an earlier finite counterexample. Its institutional original and complete later resolution history have not been authenticated. Ek's bibliography corroborates the report's authors, title and year. No first-discovery, first-counterexample or worldwide-priority claim is made.

The PDF was compiled from the included TeX. To rebuild with a TeX installation providing the standard packages used in the source, run `pdflatex proof.tex` twice from `paper/`. A rebuild can change PDF metadata or font encoding; MANIFEST.json records the distributed bytes. This research note has no assigned journal venue, and no independent human peer-review or proof-assistant certification is asserted.

Prepared with AI assistance. Third-party papers are cited rather than redistributed. WHITELIST.txt lists the complete payload; MANIFEST.json lists its file hashes, excluding itself.
