# Asymmetry-Function
#Returns an array of the fourier A1 parameter and the phase angle for a given object in the SDSS field specified
    #by run, rerun, camcol, field, row, col @ row, col.
    #r= Radius (in number of petrosian radiuses) to calculate the fourier coefficient for
    #petrorad=the petrosian radius of the object in arcseconds
    #expphi = The angle of the exponential fit, expressed as degrees, N through E
    #expAB= The ratio of the semi major axes of the disk
    # Run, rerun, camcol, field = Specified the SDSS field the object is contained in
    # rowf, colf = the pixel coordinates of the centre of the image, in FITS coordinates (ie, first pixel is 1, not zero) 
    # FITS_directory=Location of folder of fits files
