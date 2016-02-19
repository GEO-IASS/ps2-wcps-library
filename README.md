# es2-wcps-library

Formulas for extracting compositional information with OGC WCPS queries, for hyperspectral data ingested on PlanetServer/EarthServer ([http://earthserver.eu](http://earthserver.eu)

## Examples

```
for c in (frt00007032_07_if187l) 
     return
            encode (c [((0.147 - 0.105) - (0.147 + 0.105)) * ((0.147 -    0.2067) - (0.147 + 0.2067)) ], “png”);

for c in (frt00007032_07_if187l) 
     return
            encode (c [((band_a - band_b) - (band_a + band_b)) * ((band_a - band_c) - (band_a + band_c)) ], “png”);
```

# Library items 

Summary products and spectral parameters in [WCPS](https://en.wikipedia.org/wiki/Web_Coverage_Processing_Service)

_being populated, format of files and structure of library subject to change_

* [HCP](hcp.txt)


# References

Viviano-Beck, C. E., et al. (2014), Revised CRISM spectral parameters and summary products based on the currently detected mineral diversity on Mars, J. Geophys. Res. Planets, 119, 1403–1431, [doi:10.1002/2014JE004627](http://dx.doi.org/10.1002/2014JE004627 ) [pdf](http://authors.library.caltech.edu/53039/1/jgre20270.pdf)


