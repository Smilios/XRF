# XRF
Those codes are used to analyze all the data gathered from the XRF experiment.
What each code does:
"1 Gaussian Fit for Calibration" is the code used for doing a single Gaussian fit on a specific peak in the emission spectrum in order to find the mean value.
"Many Gaussian Fits for Calibration" is the code used for performing a fit of a sum of many Gaussians on many peaks in the emission spectrum in order to find the mean value of each of them. This is used when the peaks are too closed to each other.
"calibration linear fit" is the code used for performing a linear fit on the data gathered from the calibration in order to find the transfer between Energy[KeV] to channel number.
"1 Gaussian fit for normalized counts per Energy" is the code used to perform a single Gaussian fit on a single peak in order to find its mean value and area~Intensity for the data after it was transformed to Energy.
"many Gaussian fit for normalized counts per Energy" is the code used to perform a sum of many Gaussians on many peaks in the emission spectrum in order to find the mean value of each of them and area~Intensity for the data after it was transformed to Energy. This is used when the peaks are too closed to each other.
"Thickness finding with Brent's Method" is the code used to find the thickness of a sample using Brent's Method for finding roots.
