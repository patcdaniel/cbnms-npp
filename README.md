### NPP - CBNMS Condition Reports ###

NPP (Net Primary Production)  
Data Source:  The California Current merged satellite-derived 4-km dataset  
Mati Kahru, mkahru@ucsd.edu  

Net Primary Productivity is a metric for how much Carbon is generated from marine phytoplankton. It can basically be thought of as the amount of carbon dioxide phytoplankton take up during photosynthesis minus how much they respire.  

From spg-satdata.ucsd.edu:
> “Net Primary Production (NPP, mg C m-2 day-1) estimates are calculated from the 5-day merged Chla, merged daily PAR (from MODISA, MODIST, VIIRS-SNNP, VIIRS-JPSS1) and daily SST-OI data (Reynolds et al. 2007) using a modified VGPM (Behrenfeld and Falkowski 1997) called VGPM-CAL (Kahru et al. 2009). By using daily PAR and daily SST and with 5-day Chla we are assuming that Chla is changing relatively slowly and we can generate daily NPP products (Kahru et al. 2016).”
---

Spatial daily averages for all data nodes that fall with in the CBNMS sanctuary [shapefile](./shapefiles/). Data are then aggregated into a seasonal mean for each year as:
- Nov to Feb = Winter
- March to June = Upwelling
- July to Oct = Relaxation
