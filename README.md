## 
The current iteration of the RSG list is completed; future improvements are planned and will be added as soon as available. 
Other lists will also be uploaded for Wolf-Rayet and other stars soon.

# Galactic RSG Candidates 
**Latest** (August 10, 2023)


- `Final_RSG_close_stars_Catalog_8_10_2023`
    - Final list containing both methods and a list of known RSG whose proximity prevents being in Gaia DR2/DR3 data printed in the recent paper (https://doi.org/10.48550/arXiv.2307.08785)
    - Details about the meaning of column identifiers can be found in the `Column Descriptions` folder under the same name
    - Utilizes AAVSO VSX version=7.32.4
    - Warning: two objects are included that only have positional information from Gaia DR2, and so columns like ra, dec, and radial velocity are left empty while ra_dr2, dec_dr2 .. etc have values (V1061 Sco and BD-17 5117)
      
**Associated Lists** (available in the `data` folder)
- `Final_RSG_Catalog_8_10_2023`:
    - Final list that does not include the close star list 
    
    
    
- `Bright_Late_Type_Star_Catalog`:
    - Contains all late-type bright stars, used to produce `Final_RSG_Catalog_8_10_2023`
    - **Contains stars that are not SN progenitors**
    - Table 2 in the recent paper (https://doi.org/10.48550/arXiv.2307.08785)
    - Details about the meaning of column identifiers can be found in the `Column Descriptions` folder under the same name


# Old [obsolete] Versions:

- `Method_1_RSGs_catalog.csv`: :warning: This catalog is obsoleted
   - portion of the final version based on a collection of literature 

- `RSG_version_2.csv`: :warning: This catalog is obsoleted
    - Second version which includes expansion of list through Method 2, new derivation for dust extinction, and changes to how spectral type was adopted
   
- `RSG_version_1.csv`: :warning: This catalog is obsoleted
   - First version of RSG candidate list used for SNEWS, includes an analysis on luminosity and the likelihood of being an RSG
   - Regions for the likelihood of RSG status include: 
      - **Gold** - in an area of Luminosity/Effective Temperature space which should be almost complete RSGs
      - **Silver** - in an area of Luminosity/Effective Temperature space which has some AGB contamination
      - **Bronze** - in an area of Luminosity/Effective Temperature space with progressive more AGB contamination


# Galactic Supermassive Stars

- `blue_supermassive_stars.csv`: Compilation file of Blue supermassive stars from literature 
  - does not include any further analysis 
  - to be uploaded
- `yellow_supermassive_stars.csv`: Compilation file of Yellow supermassive stars from literature 
  - does not include any further analysis
  - to be uploaded
- `supermassive_stars.csv`: Compilation file of supermassive stars whose color has not been classified but has been determined as a massive star 
   - does not include any further analysis
   - to be uploaded
- `wolf_rayet_stars.csv`: Compilation file of Wolf-Rayet stars from literature
  - does not include any further analysis
  - to be uploaded

# Working with Data
- `Basic_code` :
  - code for basic manipulation of the files listed above
  


