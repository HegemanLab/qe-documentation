# Atmospheric pressure chemical ionization (APCI)

For pictures and more detail please refer to the Ion Max and Ion Max-S Source Hardware Manual pages 57-74 (install page 64)

1. Reduce temperature of HESI source.
2. Remove source when cool.
3. Remove HESI probe; take out all gas lines and voltage plug in. Store in box and protect the needle tip. Remove red LC connector line.
4. In cabinet next to QE and computer there is a blue box labeled APCI
5. Use pilers to careful insert corona needle into holder on side of source. Corona needles are in yellow envelope. (NO bend or corrosion)
6. Slide in APCI probe and attach gas and voltage lines. Attach LC connector line.

Suggested solvents:
* Solvent A: Water (NO FA)
* Solvent B: Methanol 

**Do not use FA & never use acetonitrile. It will produce a very poor signal.**

> Note: High flow rates of 200ul-2mL if < 200ul the signal is unstable

Source parameters:
* Sheath: 50
* Aux: 5
* Sweep: 1
* Current: 4 uA (do not change this)
* Cap: 200-225(MAX)
* Slens: 50
* Vap Heat: 400-450

Note: Probe position doesn’t matter for APCI

Once and awhile will need to Bake out 400-500 C then run the LC with 50/50 water methanol

Reference:
```
@article{Nordstrm2008,
  doi = {10.1021/ac701982e},
  url = {https://doi.org/10.1021/ac701982e},
  year  = {2008},
  month = {jan},
  publisher = {American Chemical Society ({ACS})},
  volume = {80},
  number = {2},
  pages = {421--429},
  author = {Anders Nordstr\"{o}m and Elizabeth Want and Trent Northen and Janne Lehti\"{o} and Gary Siuzdak},
  title = {Multiple Ionization Mass Spectrometry Strategy Used To Reveal the Complexity of Metabolomics},
  journal = {Analytical Chemistry}
}
```