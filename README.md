# LaxPairsContinuumLimit-ABS
Wolfram Mathematica notebooks to perform the continuum limits of Lax Pairs for the ABS equations Q1--Q4, H1, H3_0.

The notebooks are self-explanatory and contain the necessary code to:
- compute the discrete Lax pair for an ABS equation and its continuum limit
- Compute the zero-curvature-condition and extract the associated PDE
- Probe the structure of the Continuous Lax Pairs

In particular, the section *Notebook Options* contains all the parameters one
might wish to change before running the computations themselves.

For compatibility reasons, the results are given in a plain text file, but the
easiest way to access them is through the corresponding `*.mc` file, via the command

``` mathematica
foo=Uncompress@Import["foo.mc","String"]
```

This will store the continuous lax matrices as an association, so that, for
instance U^{(3)} can be accessed by

``` mathematica
foo[3]
```

