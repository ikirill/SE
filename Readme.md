Code I used to solve some questions on Math.SE.

- [MultiplePolylogPSLQ.py](MultiplePolylogPSLQ.py) Main code that uses
  pslq to try and compute multiple polylog values and integrals. It
  depends on sage, and mpmath, and the output is not completely clean
  either, there are emacs-lisp helper functions.
- [MultiplePolylogarithmIntegrals.nb](MultiplePolylogarithmIntegrals.nb)
  Mathematica notebook for computing polylog integrals; it depends on
  the python code above a little bit.
- [Transcendental recognize.nb](Transcendental recognize.nb) Integer
  relation algorithm based on lattice reduction; it's straightforward
  and very simple and clean, and it's not mine (apart from the hacky
  constant generation code), I copied it from somewhere on Math.SE.
- [iltwo?.txt](iltwo6.txt) Output from calculations of integrals of
  dilogarithm powers on (0, 1) in terms of multiple zeta values.
