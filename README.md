James Webb Space Telescope Data Analysis Tool Notebooks
--------------

The ``jdat_notebooks`` repository contains notebooks illustrating workflows for post-pipeline analysis of JWST data. Some of the notebooks also illustrate generic analysis workflows that are applicable to data from other observatories as well. This repository and the notebooks are one component of STScI's larger [Data Analysis Tools Ecosystem](https://jwst-docs.stsci.edu/jwst-post-pipeline-data-analysis).

The following [table](https://spacetelescope.github.io/jdat_notebooks/) summarizes the notebooks currently available.

Installation
--------------

You can view [rendered versions of the notebooks](https://spacetelescope.github.io/jdat_notebooks/), which require no special tools beyond your web browser.

To download and execute the notebooks, [clone](https://github.com/git-guides/git-clone) this repository to your local computer. Most of the notebooks
require packages that can be installed using [pip](https://pip.pypa.io/en/stable/). The version
dependencies are listed in the `environment.yaml` and in the `requirements` file in each notebook folder.

### If you locally cloned this repo before 5 Feb 2021

The primary branch for this repo has been transitioned from ``master`` to ``main``.  If you have a local clone of this repository and want to keep your local branch in sync with this repo, you'll need to do the following in your local clone from your terminal:

<pre><code>   git branch -m master main
   git fetch origin
   git branch -u origin/main main
</code></pre>

If you are using a GUI to manage your repos you'll have to find the equivalent commands as it's different for different programs. Alternatively, you can just delete your local clone and re-clone!


Help
----------

If you uncover any issues or bugs, you can open a GitHub ticket.  For faster responses, however, we encourage you to submit a JWST Help Desk Ticket: jwsthelp.stsci.edu

Contributing
----------

Contributions are welcome from both the scientist and developer community.  If you wish to contribute fixes or clarifications to existing notebooks, feel free to do so directly to this repository.  If you wish to contribute new notebooks or major reworks of existing notebooks, we refer you to [dat_pyinthesky](https://github.com/spacetelescope/dat_pyinthesky/tree/master/jdat_notebooks).  For details on how to provide such contributions, see the [contributing instructions](https://github.com/spacetelescope/jdat_notebooks/blob/main/CONTRIBUTING.md).

The notebooks attempt to utilize a number of software packages supported by STScI, including [Astropy](https://www.astropy.org), [glue](http://docs.glueviz.org/en/stable/index.html), [ginga](https://ginga.readthedocs.io/en/latest/), [photutils](https://photutils.readthedocs.io), [specutils](https://specutils.readthedocs.io/en/stable/), [astroimtools](http://astroimtools.readthedocs.io), [imexam](http://imexam.readthedocs.io), [jdaviz](https://jdaviz.readthedocs.io/en/latest/), [asdf](http://asdf.readthedocs.io/en/latest/), [gwcs](https://gwcs.readthedocs.io/en/latest/), and [synphot](http://synphot.readthedocs.io/en/latest/index.html).  Note jdaviz is STScI's JWST Data Analysis Visualization Tool, designed to be used with spectra, IFU cubes, and multi-object spectroscopy (MOS).

