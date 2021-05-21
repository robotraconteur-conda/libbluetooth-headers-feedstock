About libbluetooth-headers
==========================

Home: http://www.bluez.org/

Package license: 

Feedstock license: [BSD-3-Clause](https://github.com/robotraconteur/libbluetooth-headers-feedstock/blob/master/LICENSE.txt)

Summary: libbluetooth header files

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libbluetooth--headers-green.svg)](https://anaconda.org/r/libbluetooth-headers) | [![Conda Downloads](https://img.shields.io/conda/dn/r/libbluetooth-headers.svg)](https://anaconda.org/r/libbluetooth-headers) | [![Conda Version](https://img.shields.io/conda/vn/r/libbluetooth-headers.svg)](https://anaconda.org/r/libbluetooth-headers) | [![Conda Platforms](https://img.shields.io/conda/pn/r/libbluetooth-headers.svg)](https://anaconda.org/r/libbluetooth-headers) |

Installing libbluetooth-headers
===============================

Installing `libbluetooth-headers` from the `r` channel can be achieved by adding `r` to your channels with:

```
conda config --add channels r
conda config --set channel_priority strict
```

Once the `r` channel has been enabled, `libbluetooth-headers` can be installed with:

```
conda install libbluetooth-headers
```

It is possible to list all of the versions of `libbluetooth-headers` available on your platform with:

```
conda search libbluetooth-headers --channel r
```




Updating libbluetooth-headers-feedstock
=======================================

If you would like to improve the libbluetooth-headers recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`r` channel, whereupon the built conda packages will be available for
everybody to install and use from the `r` channel.
Note that all branches in the robotraconteur/libbluetooth-headers-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


