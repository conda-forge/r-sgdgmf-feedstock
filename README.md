About r-sgdgmf-feedstock
========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-sgdgmf-feedstock/blob/main/LICENSE.txt)


About r-sgdgmf
--------------

Home: https://github.com/CristianCastiglione/sgdGMF

Package license: MIT

Summary: Efficient framework to estimate high-dimensional generalized matrix factorization models using penalized maximum likelihood under a dispersion exponential family specification. Either deterministic and stochastic methods are implemented for the numerical maximization. In particular, the package implements the stochastic gradient descent algorithm with a block-wise mini-batch strategy to speed up the computations and an efficient adaptive learning rate schedule to stabilize the convergence. All the theoretical details can be found in Castiglione et al. (2024, <doi:10.48550/arXiv.2412.20509>). Other methods considered for the optimization are the alternated iterative re-weighted least squares and the quasi-Newton method with diagonal approximation of the Fisher information matrix discussed in Kidzinski et al. (2022, <http://jmlr.org/papers/v23/20-1104.html>).

About r-sgdgmf
--------------

Home: https://github.com/CristianCastiglione/sgdGMF

Package license: MIT

Summary: Efficient framework to estimate high-dimensional generalized matrix factorization models using penalized maximum likelihood under a dispersion exponential family specification. Either deterministic and stochastic methods are implemented for the numerical maximization. In particular, the package implements the stochastic gradient descent algorithm with a block-wise mini-batch strategy to speed up the computations and an efficient adaptive learning rate schedule to stabilize the convergence. All the theoretical details can be found in Castiglione et al. (2024, <doi:10.48550/arXiv.2412.20509>). Other methods considered for the optimization are the alternated iterative re-weighted least squares and the quasi-Newton method with diagonal approximation of the Fisher information matrix discussed in Kidzinski et al. (2022, <http://jmlr.org/papers/v23/20-1104.html>).

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27716&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sgdgmf-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27716&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sgdgmf-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27716&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sgdgmf-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27716&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sgdgmf-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27716&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sgdgmf-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27716&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sgdgmf-feedstock?branchName=main&jobName=win&configuration=win%20win_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27716&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sgdgmf-feedstock?branchName=main&jobName=win&configuration=win%20win_64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--sgdgmf-green.svg)](https://anaconda.org/conda-forge/r-sgdgmf) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-sgdgmf.svg)](https://anaconda.org/conda-forge/r-sgdgmf) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-sgdgmf.svg)](https://anaconda.org/conda-forge/r-sgdgmf) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-sgdgmf.svg)](https://anaconda.org/conda-forge/r-sgdgmf) |

Installing r-sgdgmf
===================

Installing `r-sgdgmf` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-sgdgmf` can be installed with `conda`:

```
conda install r-sgdgmf
```

or with `mamba`:

```
mamba install r-sgdgmf
```

It is possible to list all of the versions of `r-sgdgmf` available on your platform with `conda`:

```
conda search r-sgdgmf --channel conda-forge
```

or with `mamba`:

```
mamba search r-sgdgmf --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-sgdgmf --channel conda-forge

# List packages depending on `r-sgdgmf`:
mamba repoquery whoneeds r-sgdgmf --channel conda-forge

# List dependencies of `r-sgdgmf`:
mamba repoquery depends r-sgdgmf --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-sgdgmf-feedstock
===========================

If you would like to improve the r-sgdgmf recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-sgdgmf-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/r](https://github.com/orgs/conda-forge/teams/r/)

