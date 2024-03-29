### MODIS (Aqua) Land Surface Reflectance (Bands 1, 2, 1)
Temporal Coverage: 1 January 2007 - present

False Color: Red= Band 1, Green = Band 2, Blue = Band 1

Vegetation is very reflective in the near infrared (Band 2), and absorbent in Band 1. Assigning band 2 to green means even the smallest hint of vegetation will appear bright green in the image. Liquid water on the ground will be very dark since it absorbs in the red and the SWIR and sediments in water appear pink. This band combination is good for identifying vegetation changes, drought and floods.

The MODIS Land Surface Reflectance product is available from both the Terra (MOD09) and Aqua (MYD09) satellites. The sensor resolution is 250 m, imagery resolution is 250 m, and the temporal resolution is daily.

### MODIS Corrected Reflectance vs. MODIS Surface Reflectance

The MODIS Corrected Reflectance algorithm utilizes MODIS Level 1B data (the calibrated, geolocated radiances). It is not a standard, science quality product. The purpose of this algorithm is to provide natural-looking images by removing gross atmospheric effects, such as Rayleigh scattering, from MODIS visible bands 1-7. The algorithm was developed by the original MODIS Rapid Response team to address the needs of the fire monitoring community who want to see smoke. Corrected Reflectance shows smoke more clearly than the standard Surface Reflectance product. In contrast, the MODIS Land Surface Reflectance product (MOD09) is a more complete atmospheric correction algorithm that includes aerosol correction, and is designed to derive land surface properties. In clear atmospheric conditions the Corrected Reflectance product is very similar to the MOD09 product, but they depart from each other in presence of aerosols. If you wish to perform a complete atmospheric correction, please do not use the Corrected Reflectance algorithm. An additional difference is that the Land Surface Reflectance product is only tuned for calculating the reflectance over land surfaces.

References: [MODAPS - MOD09](https://modaps.modaps.eosdis.nasa.gov/services/about/products/c6-nrt/MOD09.html);[MODAPS - MYD09](https://modaps.modaps.eosdis.nasa.gov/services/about/products/c6-nrt/MYD09.html); [NASA Earthdata - Creating Reprojected True Color MODIS Images: A Tutorial](https://earthdata.nasa.gov/sites/default/files/field/document/MODIS_True_Color.pdf)
