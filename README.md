# Eclipsing Binary Star Light Curve Analysis

This project analyzes V-band FITS images of the eclipsing binary star system J23265+1230 using Python. The goal was to reduce raw astronomical image data, perform aperture photometry, build a relative light curve, and compare the observed eclipse behavior with the expected orbital period.

## Tools Used

- Python
- NumPy
- Matplotlib
- Astropy
- Photutils
- Jupyter Notebook

## Methods

- Loaded astronomical FITS image data
- Applied bias subtraction and flat-field correction
- Performed aperture photometry on the target star and reference stars
- Built a relative light curve using differential photometry
- Detrended baseline systematics
- Phase-folded the light curve using the expected orbital period
- Estimated primary and secondary eclipse depths

## Results

The final relative light curve showed a clear primary eclipse and a shallower secondary eclipse, consistent with an eclipsing binary system. The period scan produced a broad minimum near the expected orbital period, with limitations from time coverage and observational systematics.

## Notes

The original FITS image files are not included due to file size. The notebook documents the full analysis workflow using local data files.
