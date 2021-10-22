About gnuradio-paint
====================

Home: https://github.com/drmpeg/gr-paint

Package license: GPL-3.0-or-later

Feedstock license: [BSD-3-Clause](https://github.com/YOUR_GITHUB_USER_OR_ORG/gnuradio-oot-template-feedstock/blob/master/LICENSE.txt)

Summary: Template package of a GNU Radio module.

Development: https://github.com/drmpeg/gr-paint

Documentation: https://github.com/drmpeg/gr-paint

Template package of a GNU Radio module. This example builds a package for gr-paint. You can modify the files in the 'recipe' directory and 'conda-forge.yml' to build any OOT module!


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gnuradio--paint-green.svg)](https://anaconda.org/YOUR_ANACONDA_CHANNEL/gnuradio-paint) | [![Conda Downloads](https://img.shields.io/conda/dn/YOUR_ANACONDA_CHANNEL/gnuradio-paint.svg)](https://anaconda.org/YOUR_ANACONDA_CHANNEL/gnuradio-paint) | [![Conda Version](https://img.shields.io/conda/vn/YOUR_ANACONDA_CHANNEL/gnuradio-paint.svg)](https://anaconda.org/YOUR_ANACONDA_CHANNEL/gnuradio-paint) | [![Conda Platforms](https://img.shields.io/conda/pn/YOUR_ANACONDA_CHANNEL/gnuradio-paint.svg)](https://anaconda.org/YOUR_ANACONDA_CHANNEL/gnuradio-paint) |

Installing gnuradio-paint
=========================

Installing `gnuradio-paint` from the `YOUR_ANACONDA_CHANNEL` channel can be achieved by adding `YOUR_ANACONDA_CHANNEL` to your channels with:

```
conda config --add channels YOUR_ANACONDA_CHANNEL
conda config --set channel_priority strict
```

Once the `YOUR_ANACONDA_CHANNEL` channel has been enabled, `gnuradio-paint` can be installed with:

```
conda install gnuradio-paint
```

It is possible to list all of the versions of `gnuradio-paint` available on your platform with:

```
conda search gnuradio-paint --channel YOUR_ANACONDA_CHANNEL
```




Updating gnuradio-paint-feedstock
=================================

If you would like to improve the gnuradio-paint recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`YOUR_ANACONDA_CHANNEL` channel, whereupon the built conda packages will be available for
everybody to install and use from the `YOUR_ANACONDA_CHANNEL` channel.
Note that all branches in the YOUR_GITHUB_USER_OR_ORG/gnuradio-paint-feedstock are
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

* [@LandoCalrissian](https://github.com/LandoCalrissian/)
* [@LisaSimpson](https://github.com/LisaSimpson/)

