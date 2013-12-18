# Replication of results for *The socio-cultural sources of urban buzz*

- Author: [Dani Arribas-Bel](http://darribas.org)

This the site that presents the data, code and steps required to reproduce the figures and results presented in the paper *The socio-cultural sources of urban buzz*, by Daniel Arribas-Bel, Karima Kourtit and Peter Nijkamp, accepted for publication in *Environment and Planning C*. If you find this interesting and use parts of it, we would appreciate if you could properly cite it in the following way:

```bibtex
@article{arribasbel_kourtit_nijkamp_epc,
	author = "Arribas-Bel, Daniel and Kourtit, Karima and Nijkamp, Peter",
	journal = "Environment and Planning C – Government and Policy",
	title = "{The socio-cultural sources of urban buzz}",
	year = "in press"
}
```

#### Distribution, data sources and license

This document is hosted, together with the data required, as an open repository that is available in the following url:

- https://github.com/darribas/buzz_adam

The data are provided "as is" and have been aggregated and aligned from the following sources:

- CBS 2011 neighborhood statistics [(link)](http://www.cbs.nl/nl-NL/menu/themas/dossiers/nederland-regionaal/publicaties/geografische-data/archief/2011/default.htm).
- BAG for land-use data [(link)](http://bag.vrom.nl).
- Foursquare data from [Chen et al. (2011)](http://infolab.tamu.edu/static/users/zhiyuan/icwsm_2011_readme.pdf).

The code and text presented here is authored by Daniel Arribas-Bel and licensed under a Creative-Commons license:

#### Dependencies

In order to run this notebook in your own machine, you will need the following libraries installed in your machine:

* [`IPython`](http://ipython.org) notebook
* [`Pandas`](http://pandas.pydata.org)
* [`PySAL`](http://pysal.org)
* [`Statsmodels`](http://statsmodels.sourceforge.net/)
* The methods `dbf2df` and `df2dbf`, part of the GeoDa sandbox, hosted [here](https://github.com/GeoDaSandbox/sandbox/blob/master/pyGDsandbox/dataIO.py). You can read about how to install them [here](http://geodasandbox.github.io/2012/03/28/how-to-get-up-and-running-with-the-geoda-center-sandbox/).

Besides this Python installation, the spatial models are estimated using [R](http://r-project.org) and its `spdep` package.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span
xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text"
property="dct:title" rel="dct:type">"Replication of results for The
socio-cultural sources of urban buzz"</span> by <a
xmlns:cc="http://creativecommons.org/ns#" href="http://darribas.org"
property="cc:attributionName" rel="cc:attributionURL">Daniel Arribas-Bel</a>
is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by/4.0/">Creative Commons
Attribution 4.0 International License</a>.
