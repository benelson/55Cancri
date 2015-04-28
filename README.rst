55Cancri
========

This is a repository for posterior samples of the 55 Cancri planetary system. Methodological and science details can be found `here <http://adsabs.harvard.edu/abs/2014MNRAS.441..442N>`_.

How to read these files
-----------------------

Each line contains 68 values. They read as follows.


MCMC information::

Column 1: Markov chain generation
Column 2: Markov chain index
Column 3: Chi squared with jitter penalty term


Orbital Parameter information. Each planet has 9 parameters::

Columns 4, 13, 22, 31, 40: Orbital period in [days] for planets "e", "b", "c", "f", and "d" respectively.
Columns 5, 14, 23, 32, 41: RV half amplitude in [m/s] for planets "e", "b", "c", "f", and "d" respectively.
Columns 6, 15, 24, 33, 42: mass in [solar masses] for planets "e", "b", "c", "f", and "d" respectively.
Columns 7, 16, 25, 34, 43: semi-major axis in [AU] for planets "e", "b", "c", "f", and "d" respectively.
Columns 8, 17, 26, 35, 44: eccentricity for planets "e", "b", "c", "f", and "d" respectively.
Columns 9, 18, 27, 36, 45: inclination in [degrees] for planets "e", "b", "c", "f", and "d" respectively.
Columns 10, 19, 28, 37, 46: argument of pericenter in [degrees] for planets "e", "b", "c", "f", and "d" respectively.
Columns 11, 20, 29, 38, 47: longitude of ascending node in [degrees] for planets "e", "b", "c", "f", and "d" respectively.
Columns 12, 21, 30, 39, 48: mean anomaly at the epoch of the first Lick observation in [degrees] for planets "e", "b", "c", "f", and "d" respectively.


Instrumental parameter information::

Columns 49, 50, 51, 52, 53: Lick observatory RV offsets
Columns 54, 55: Keck HIRES RV offsets
Column 56: HET RV offset
Column 57: HJST RV offset

Columns 58, 59, 60: Lick observatory jitters
Column 61: Keck jitter
Column 62: HET jitter
Column 63: HJST jitter


Supplementary information::

Column 64: Chi squared without jitter
Column 65: Run length (number of subsequent states in the Markov chain without an Metropolis-Hastings acceptance)
Column 66: Chi squared with jitter (no penalty term)
Column 67: Stellar radius in [AU]
Column 68: Stellar mass in [solar masses]


Attribution
-----------

Please cite `Nelson et al. (2014) <http://adsabs.harvard.edu/abs/2014MNRAS.441..442N>`_ if you use these posterior samples in your research.

The BibTeX entry for the paper is::

    @ARTICLE{2014MNRAS.441..442N,
	author = {{Nelson}, B.~E. and {Ford}, E.~B. and {Wright}, J.~T. and {Fischer}, D.~A. and {von Braun}, K. and {Howard}, A.~W. and {Payne}, M.~J. and {Dindar}, S. },
    	 title = "{The 55 Cancri planetary system: fully self-consistent N-body constraints and a dynamical analysis}",
       journal = {\mnras},
 archivePrefix = "arXiv",
        eprint = {1402.6343},
  primaryClass = "astro-ph.EP",
      keywords = {methods: statistical, techniques: radial velocities, planets and satellites: dynamical evolution and stability},
          year = 2014,
         month = jun,
        volume = 441,
         pages = {442-451},
           doi = {10.1093/mnras/stu450},
        adsurl = {http://adsabs.harvard.edu/abs/2014MNRAS.441..442N},
       adsnote = {Provided by the SAO/NASA Astrophysics Data System}
    }
