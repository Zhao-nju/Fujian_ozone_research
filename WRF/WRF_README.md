# WRF
## Model settings
The model settings are specified in **namelist.input**.
  
## Emission
### Anthropogenic emission
Anthropogenic emissions were obtained from the 2019 Multi-resolution Emission Inventory for China (MEIC).  
MEIC can be obtained at http://meicmodel.org.cn  
We used the **meic2wrf** tool to convert the MEIC Inventory to WRF input data.  
The tool **meic2wrf** can be downloaded at https://github.com/jinfan0931/meic2wrf.  
### Biogenci emission
Biogenic emissions were calculated online using the Model of Emissions of Gas and Aerosols from Nature (**MEGAN**).  
Megan model and related biogenic emission data can be downloaded at https://www.acom.ucar.edu/wrf-chem/download.shtml.  
