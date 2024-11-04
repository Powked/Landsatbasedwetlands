This readme file was generated on [2024-11-04] by [Alexis ROY]

## GENERAL INFORMATION

**Title of Dataset:**  
Landsat-based remote sensing of surface water dynamics in southern African wetlands in drylands from 1986 to 2022

**Author/Principal Investigator Information**  
- **Name:** Alexis ROY  
- **ORCID:** 0000-0001-7885-4389  
- **Institution:** Université Paris-Saclay, CNRS, AgroParisTech, Ecologie Systématique et Evolution, 91190, Gif-sur-Yvette, France  
- **Address:** 12 rue 128, 91190 Gif-sur-Yvette  
- **Email:** alexis.roy1@universite-paris-saclay.fr  

**Author/Associate or Co-investigator Information**  
- **Name:** Florence HULOT  
- **ORCID:** 0000-0002-8897-3987  
- **Institution:** Université Paris-Saclay, CNRS, AgroParisTech, Ecologie Systématique et Evolution, 91190, Gif-sur-Yvette, France  
- **Address:** 12 rue 128, 91190 Gif-sur-Yvette  
- **Email:** florence.hulot@universite-paris-saclay.fr  

- **Name:** Kamel SOUDANI  
- **ORCID:** 0000-0002-3468-5648  
- **Institution:** Université Paris-Saclay, CNRS, AgroParisTech, Ecologie Systématique et Evolution, 91190, Gif-sur-Yvette, France  
- **Address:** 12 rue 128, 91190 Gif-sur-Yvette  
- **Email:** kamel.soudani@universite-paris-saclay.fr  

**Date of data collection:**  
From 2022-10-01 to 2023-01-01

**Geographic location of data collection:**  
Google Earth Engine

**Information about funding sources that supported the collection of the data:**  
This work was supported by the French National Program EC2CO (Ecosphère Continentale et Côtière) and by the Centre National d'Études Spatiales.

## SHARING/ACCESS INFORMATION

- **Licenses/restrictions placed on the data:**  
  [Specify if applicable]

- **Links to publications that cite or use the data:**  
  [Add links if available]

- **Links to other publicly accessible locations of the data:**  
  [Add links if available]

- **Links/relationships to ancillary data sets:**  
  [Specify if applicable]

- **Was data derived from another source?**  
  If yes, list source(s): [Specify source if applicable]

- **Recommended citation for this dataset:**  
  [Provide citation if available]

## DATA & FILE OVERVIEW

**File List**  

1. **Data**  
   - **Calcul_check.xlsx**: Calculation verification. Not used in the code but included as supporting information.

2. **ERA_Precip_Monthly.csv**:  
   Cumulative monthly precipitation data from ERA-5, from 1985 to 2020.

3. **ERA_Temp_Monthly.csv**:  
   Average monthly temperature data from ERA-5, from 1985 to 2020.

4. **Images_per_year_WaterMap.csv**:  
   Number of Landsat images used to calculate water frequencies.

5. **Points Valid**  
   - LANDSAT_DATA_Points_Validation_Complet.xlsx  
   - LANDSAT_Data_PointsValidation.xls  
   - LANDSAT_Data_PointsValidation.xlsx  
   - PTSinfos.csv  
   - PTSinfos_complet.csv  
   - TSPTS.csv  
   - TSPTS_complet.csv  
     
   Detection and localization data for wetlands validation points used in the paper. Additional information is available in the file.

6. **Code**  
   - **Validation_of_WFreq_deposit.ipynb**: Code used to validate the efficiency of the methodology.
   - **Times_Series_ValidationPoints_notPump_dépot.ipynb**: Code used to produce heatmaps of water frequency, and the distribution of precipitation, temperature, water frequency, anomalies, and statistical analysis.

**Relationship between files**  
`Times_Series_ValidationPoints_notPump_dépot.ipynb` uses `ERA_Precip_Monthly.csv`, `ERA_Temp_Monthly.csv`, `TSPTS_complet.csv`, and `PTSinfos_complet.csv`.

## METHODOLOGICAL INFORMATION

**Description of methods used for collection/generation of data**  
The protocol is detailed in the article *Landsat-based remote sensing of surface water dynamics in southern African wetlands in drylands from 1986 to 2022*. The data were collected using Google Earth Engine. Code is available here: [https://code.earthengine.google.com/1108638880362911b1c6d8eaf27bcbc6](https://code.earthengine.google.com/1108638880362911b1c6d8eaf27bcbc6).

**Methods for processing the data**  
To process the data, adjust the file paths accordingly.

**People involved with sample collection, processing, analysis, and/or submission**  
The Google Earth Engine code was mainly written by Kamel SOUDANI, with contributions from Alexis ROY. Data analysis and production were performed by Alexis ROY and Kamel SOUDANI.
