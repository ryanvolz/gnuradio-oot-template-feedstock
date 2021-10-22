This is a template recipe/feedstock for creating conda packages of GNU Radio out-of-tree modules. Branch names follow the GNU Radio convention for building against different major versions (you can ignore the "rendered" branches).

Instructions
====================

Modify the recipe
-----------------

First, modify the files in the `recipe` directory to suit a particular OOT module (the example builds a package for gr-paint).

1. The most important file is the `meta.yaml` file, where you will have to set the package name and version, update the dependencies, and include informational metadata.
2. You may also have to edit the build scripts, `build.sh` and `bld.bat`, to modify the build procedure.

You can then use this recipe to build a conda package using `conda build`.

Enable CI builds
----------------

If you want to create packages through the Github Actions CI infrastructure, there are some additional steps.

1. (optional) Edit the `recipe/conda_build_config.yaml` file to include your Anaconda.org channel name for uploading packages.
2. (optional) Edit the `conda-forge.yml` file to include your Anaconda.org channel and Github username.
3. (optional) Set the `BINSTAR_TOKEN` secret on your Github repository to the value of your Anaconda.org access token. This will enable uploading of the built packages to your Anaconda.org channel.
4. Render the feedstock using `conda smithy`. From the base repository directory, run the command `conda smithy rerender -c auto` to create and commit the CI infrastructure files.

To update the recipe in the future, you should create commits on a separate git branch and test them out with a pull request to the base branch. Remember to always re-render when you make changes to the recipe! Once the CI build passes, you can merge the pull request and new packages will be built and uploaded as Github Actions artifacts and (optionally) to Anaconda.org.
