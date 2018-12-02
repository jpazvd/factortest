# FACTORTEST: Stata module to perform tests for appropriateness of factor analysis

## Abstract

factortest performs the Bartlett's test for sphericity and the Kaiser-Meyer-Olkin Measure of Sampling Adequacy. Both tests should be used prior to a factor or a principal component analysis.

### Technical details

    Determinant of the matrix of correlation: This determinant will equal 1.0 only if all
    correlations equal 0, otherwise the determinant will be less than 1.

    Bartlett's test for sphericity: Calculates the determinant of the matrix of the sums of
    products and cross-products (S) from which the intercorrelations matrix is derived. The
    determinant of the matrix S is converted to a chi-square statistic and tested for
    significance.
    
    The null hypothesis is that the intercorrelation matrix comes from a population in which the
    variables are noncollinear (i.e. an identity matrix), and that the non-zero correlations in
    the sample matrix are due to sampling error.
    
    Kaiser-Meyer-Olkin Measure of Sampling Adequacy: is an index for comparing the magnitudes of
    the observed correlation coefficients to the magnitudes of the partial correlation
    coefficients.
    
    Large values for the KMO measure indicate that a factor analysis of the variables is a good
    idea.
    
                                90 or above, excelent
                                80 or above, meritorious
                                70 or above, middling
                                60 or above, mediocre
                                50 or above, miserable; and
                                below .50, unacceptable.



## Suggested Citation
[Joao Pedro Azevedo, 2003. "FACTORTEST: Stata module to perform tests for appropriateness of factor analysis," Statistical Software Components S436001, Boston College Department of Economics, revised 27 Aug 2006.](https://ideas.repec.org/c/boc/bocode/s436001.html)

### Handle: RePEc:boc:bocode:s436001 

## References

    Box,G.E.P.(1949) "A general distribution theory for a class of likelihood criteria."
        Biometrica, 36: 317-346.

    Cureton, E.E., & D'Agostino, R.B. (1983). Factor analysis: An applied approach. Hillsdale, NJ:
        Erlbaum.

### Note: 
This module may be installed from within Stata by typing "ssc install factortest". Windows users should not attempt to download these files with a web browser.

### Keywords
factor analysis; principal components; sphericity; sampling adequacy;