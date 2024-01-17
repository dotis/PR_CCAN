## PR CCAN project 
### Climate adaptation (also includes USVI)

### Notes from Meeting w/Laura, Pablo and Digna on 1/17/24:
1. Looking at heat vulnerability in San Juan and Ponce
2. Interested in how spatial patterns of heat were affected by Hurricane Maria in 2017
3. Use Landsat 8 for consistency. Expand on earlier HVI work (2017)
4. Which algorithm to use for Landsat LST: (Four compared [HERE](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7147158/))
   - Basic NDVI based emissivity approach; water vapor not accounted for [REF](https://giscrack.com/how-to-calculate-land-surface-temperature-with-landsat-8-images/)
   - Split-window (Du et al. 2015); [REF](https://www.mdpi.com/2072-4292/7/1/647)
   - Can get w (water vapor) from NCEP (use climatology?)
   - Another SW (paywalled, but ref in Zotero) [REF](https://ieeexplore.ieee.org/document/4689350)
   -  
