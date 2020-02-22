ghc-api-compat
==============

We are in the process of `renaming GHC modules <https://gitlab.haskell.org/ghc/ghc/issues/13009>`_.

This package aims to make the transition easier by mapping old module names to
newer module names.

Build with:

.. code::

   cabal new-build -w /path/to/ghc/HEAD/_build/stage1/bin/ghc
