# Testing New Genotyping Primers for KO Validation
2026-10-08 [Issue #1](https://github.com/rmaronick/tfcb_2026_demo/issues/1)

## Reagents
| reagent | vendor | catalog number | stock concentration | final concentration |
| ------- | ------ | -------------- | ------------------- | ------------------- |
| PCR grade water | Roche | 3315959001 | n/a | n/a|
| F primer | IDT | n/a | 10 uM | 0.3 uM |
| R primer | IDT | n/a | 10 uM | 0.3 uM |
| KOD One 2x MM | Toyobo | KMM-201 | n/a | n/a|

## Procedure
1. Thaw PCR reagents and template DNA
2. Prepare a PCR master mix containing PCR-grade water, KOD One PCR Master Mix, and genomic DNA according to the volumes listed above.
3. Aliquot 18.8 μL of the prepared master mix into each PCR tube.
4. Add 0.6 uL of both F and R primer to each reaction, bringing the total reaction volume to 20 μL.
5. Mix gently and briefly centrifuge to collect the reaction mixture at the bottom of each tube.
6. Place reactions into a thermocycler and run the KOD One touchdown PCR protocol (KODTD):
   - **Initial annealing temperature: 68°C   
   - **Annealing temperature: progressively decreased during touchdown cycles 
   - **Extension: short extension time appropriate for amplicons less than 1 kb
   - **Total run time: approximately 40 minutes
7. Run PCR products on 2% agarose gel
8. If bands exist at 250-500 bp, clean up PCR reaction using Zymo's "DNA Clean and Concentrator - 5" kit protocol
9. Send samples for sanger sequencing through genewiz with the following guidelines
   - **PCR product: 25 ng
   - **Sequencing primer (10 uM): 2.5 uL
   - **Water: to 15 uL total

## Result
![PCR amplification gel](img/220_2026-10-08_11h09m36sGelGreen.jpg)
