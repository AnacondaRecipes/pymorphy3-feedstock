
# About pymorphy3
===========================

Feedstock license: [BSD-3-Clause](https://github.com/AnacondaRecipes/pymorphy3/blob/main/LICENSE.txt)

Home: https://github.com/no-plagiarism/pymorphy3

Package license: MIT

Summary: Morphological analyzer (POS tagger + inflection engine) for Russian language.


Installing pymorphy3
================

`pymorphy3` can be installed with:

```
conda install pymorphy3
```

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating pymorphy3-feedstock
========================

If you would like to improve the pymorphy3 recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@skupr-anaconda](https://github.com/skupr-anaconda/)

