# NIRSpec_MOS_JWebbinar
Draft notebooks for upcoming JWebbinar  
Final versions will be staged elsewhere on [STScI Github JWebbinar prep](https://github.com/spacetelescope/jwebbinar_prep)


[**JWebbinar**](https://www.stsci.edu/jwst/science-execution/jwebbinars)  
June 27, 2024 10AM – 12PM EDT  
[Registration](https://www.surveymonkey.com/r/JWebbinar_June_2024) closes June 21

### JWST NIRSpec MOS Data Reduction

This webinar will cover NIRSpec MOS (multi-object spectroscopy) data reduction by the JWST pipeline with example notebooks. We will cover recent pipeline updates that deliver improved spectra with default settings. We'll also discuss lingering caveats, workarounds, and techniques to reprocess data, including editing the MSA metafile and master background subtraction.

### Notebooks
* [pipeline](NIRSpec_MOS_pipeline.ipynb)
* [slits to sky](NIRSpec_MOS_slits_to_sky.ipynb)
* [MSA metafile](NIRSpec_MOS_MSA_metafile.ipynb)
* master background
* [NSClean](https://github.com/spacetelescope/jdat_notebooks/tree/main/notebooks/NIRSpec_NSClean.ipynb)

### Data
Notebooks will automatically download data as needed from MAST and/or other locations listed below.

Some files mirrored here in [data](data) subdirectory, except for large files linked below

ERO 
[SMACS0723](https://webbtelescope.org/contents/news-releases/2022/news-2022-035):
* NIRCam F200W image: [`smacs0723-grizli-v7.0-f200w-clear_drc_sci.fits.gz`](https://s3.amazonaws.com/grizli-v2/JwstMosaics/v7/smacs0723-grizli-v7.0-f200w-clear_drc_sci.fits.gz)
* NIRCam SW color image (optional) produced by [Trilogy](https://github.com/dancoe/trilogy):
[`smacs0723_color_sw.png`](https://relics.stsci.edu/data/smacs0723-73/JWST/smacs0723_color_sw.png)
* MSA shutter image: [`2736.p1c1-2e1n1.csv`](data/2736.p1c1-2e1n1.csv)
* Spec3 spectrum for source #6355:
  * S2D: [`jw02736-o007_s06355_nirspec_f290lp-g395m_s2d.fits`](data/jw02736-o007_s06355_nirspec_f290lp-g395m_s2d.fits)
  * X1D: [`jw02736-o007_s06355_nirspec_f290lp-g395m_x1d.fits`](data/jw02736-o007_s06355_nirspec_f290lp-g395m_x1d.fits)
