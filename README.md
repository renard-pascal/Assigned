# MFAssignR
Package: MFAssignR
Type: Package
Title: Molecular Formula Assignment using CHOFIT Algorithm
Version: 0.0.1
Author: Simeon Schum, Lynn Mazzoleni, Laura Brown
Maintainer: Simeon Schum, <skschum@mtu.edu>
Description: This package contains functions that can estimate
	the signal-to-noise for raw mass spectra, provide
	preliminary identification of potential isotopic masses, 
	recalibrate mass spectral data, and assign molecular formulas 
	to exact mass measurements from ultrahigh resolution mass spectral
	data using either Orbitrap MS or FT-ICR MS. The core algorithm for
	formula assignment is the CHOFIT algorithm developed by 
	Green and Perdue, Anal. Chem. (2015). This algorithm has 
	been expanded on, using formula extension to increase its
	performance and data quality.
License: GNU GPL-2
Encoding: UTF-8
LazyData: true
Depends: R (>= 3.4.1)
Imports: dplyr (>= 0.7.6),
         tidyr (>= 0.8.1),
         ggplot2 (>= 3.0.0)
RoxygenNote: 6.0.1
Suggests: knitr,
    rmarkdown
VignetteBuilder: knitr
