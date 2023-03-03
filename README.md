# Sequence Handles Design for Polycube Project:
1. Design the Sequences.
2. Choose the sequences according to appropriate Tm (15<x<17), CG contents 50%, and Salt Concentration (15mM Mg and 5mM Na) ~2600 sequences.
3. Compute the Inversed Sequences.
4. Compute dGs of the Correct Sequences (nupack condition: 50 mM Na, 0 mM Mg).
5. Compute dGs for the Spurious Sequences.
6. Find the ddG threshold such that ddG = dG correct - dG spurious = ~-3.4 kcal/mol.
7. Iterate over the forward sequences list until it found 48 strands with crosstalk <= -3.4.
8. Check the ddG using the 3rd script.
9. Check the pair probability matrix among the sequences using the 4th script.
