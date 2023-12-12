# Exploration of Biodiversity Intactness Loss in Phoenix, Arizona 

**Goal**: The goal of this project was to identify and visualize the change in biodiversity intactness in Phoenix over the years 2017 to 2020. This was achieved using a Biodiverity Intactness Index (BII) measure over the entire Phoenix area, accessed from the Microsoft Planetary Computer (MPC). We compared the BII from 2017 and 2020 to determine areas where there had been a change. The area of interest was found using shapefiles from the US census bureau, and allowed us to investigate Phoenix, Arizona. 

Analysis Steps:
1. Load in Phoenix shapefile
2. Load in rasters with BII data for 2017 and 2020 from the MPC
3. Clip the rasters to the Phoenix gemoetry
4. Determine the change in BII from 2017 to 2020
5. Visualize the areas that changed across those years

# Citations

Data was accessed from these sources:

[US Census TIGER Shapefiles](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions)

[Microsoft Planetary Computer Data Catalog](https://planetarycomputer.microsoft.com/catalog)

## File Structure 
  biodiversity-loss-phoenix  
   │   README.md  
   │   bii_phoenix.ipynb      
   │
   └───data
        │  tl_2022_04_cousub
             tl_2022_04_cousub.cpg
             tl_2022_04_cousub.dbf
             tl_2022_04_cousub.prj
             tl_2022_04_cousub.shp
             tl_2022_04_cousub.shx
    
