Eksempler på raster i python
==============================
Eksemplerne er skrevet i ipython notebooks.

ipython notebook kan installeres som beskrevet nedenfor. Med en lokal installation kan man selv rette i koden og eksekvere den igen.

Uden installation
-------------------
Hvis der kun er behov for at kigge, kan notebooks i dette repository vises via [nbviewer]( http://nbviewer.ipython.org/github/asgerpetersen/python_raster_examples/tree/master/notebooks/).


Installation
----------------

Installér ipython
```bash
mkvirtualenv ipython
pip install "ipython[notebook]"
```

Installér rasterio. Se evt [installationsvejledningen](https://github.com/mapbox/rasterio#installation)

```bash
pip install numpy
pip install rasterio
```

Start notebook
```bash
ipython notebook
```