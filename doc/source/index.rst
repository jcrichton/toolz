
PyToolz API Documentation
=========================

The Toolz project provides a set of utility functions for iterators, functions,
and dictionaries.  These functions are designed to interoperate well, forming
the building blocks of common data analytic operations.  They extend the
standard libraries `itertools` and `functools` and borrow heavily from the standard libraries of contemporary functional languages.

Toolz provides a suite of functions which have the following virtues:

-   **Composable:** They interoperate due to their use of core data structures.
-   **Pure:**  They don't change their inputs or rely on external state.
-   **Lazy:**  They don't run until absolutely necessary, allowing them to support large streaming data sets.

This gives developers the power to write *powerful* programs to solve *complex
problems* with relatively *simple code* which is *easy to understand* without
sacrificing *performance*.  Toolz enables this approach, commonly associated
with functional programming, within a natural Pythonic style suitable for
most developers.

BSD licensed source code is available at http://github.com/pytoolz/toolz/ .


Contents
^^^^^^^^

.. toctree::
   :maxdepth: 2

   heritage.rst
   install.rst
   composition.rst
   purity.rst
   laziness.rst
   control.rst
   curry.rst
   api.rst
   references.rst
