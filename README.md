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

# References
