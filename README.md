# Modernizing SYMMOL

This repository contains a modernized version of the SYMMOL code, by [Tullio Pilati](http://orcid.org/0000-0002-2310-2005) and [Alessandra Forni](https://scholar.google.com/citations?user=qZpOIqcAAAAJ).

The software was described in this paper: [“SYMMOL: a program to find the maximum symmetry group in an atom cluster, given a prefixed tolerance”](https://doi.org/10.1107/S0021889898002180), T. Pilati and A. Forni, J. Appl. Cryst. (1998). 31, 503-504, [DOI: 10.1107/S0021889898002180](https://doi.org/10.1107/S0021889898002180)


## How is this code licensed?

I have absolutely no idea, it is not stated in the file or in the paper. I have found multiple copies of it distributed with various projects, so I am hosting it here in good faith, believing its authors intended to distribute it widely.


## What is the history of this code?

The version imported in this repository was found at https://www.mtg.msm.cam.ac.uk/files/symmol.zip/view
It states:

```
SYMMOL: Version 28.04.1998
==========================================================
By Tullio Pilati and Alessandra Forni
C.N.R. - C.S.R.S.R.C. Via Golgi, 19 I-20133 Milano Italy
E-MAIL: pila@sg1.csrsrc.mi.cnr.it (T. Pilati)
E-MAIL: aforni@rs18.csrsrc.mi.cnr.it (A. Forni)
==========================================================
```

However, the `VERSION_TXT` file inside that download says:

```
Version october 22th 2002.

Dr. Tomoji Ozeki, Department of Chemistry and Material Science, Tokyo Institute
of Technology, noticed that the old version of SYMMOL, when treats a group with
degenerated inertia moment, does not minimize the RMS. The new version does.
The difference, in terms of RMS, is in the range 0.5*RMSold < RMSmin < RMSold;
in terms of symmetrized coordinates the difference is very small.
```

I am not aware of any more recent version that this.
