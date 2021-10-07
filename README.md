# Phy2026_XXCygni

Contains Jupyter Notebooks developed for the calibration and analysis of the data for the XXCygni experiment.

- `XXCygny_FlatField.ipynb` is a notebook teaching the steps required to flat-field the images for the experiment. As a test, I am using images observed in the night `2018-10-01`
- `XXCygni_Photometry.ipynb` teaches how to use Astropy `photoutils` to perform aperture photometry in one of the XXCygni images. 

I added a directory `/2010-10-01/working` which contains the test iamges I am using while developping the scripts.
- `apass_xxcygni_FOV.fits` is a photometric catalogue I retreived from APASS, which gives us reference stars in the FOV of XXCygni
- `f_CCD...fits` are flat-fielded images, proessed using `XXCygny_FlatField.ipynb` 
- `a_CCD_...fits` are images aligned by Tom's script `XXCygny_aligning.ipynb`
- `wcs_CCD_Image_0118.fits` is the WCS reference image that I obtained by processing `a_CCD_Image_0118.fits` with astrometry.net
