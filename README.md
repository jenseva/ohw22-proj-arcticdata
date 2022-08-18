# ohw22-proj-arcticdata

## Title:
Arctic in-situ observing data discovery, access, and visualization

## Summary:
Plan for a data management infrastructure for data discovery, access and visualization of key Arctic data sets from GOMO Arctic research funded platforms for use by scientists and other end-users. Currently GOMO Arctic datasets are available through a number of different data sources each with their own formats and access protocols. The intent of this project is to get insight on approaches for making this data available through a common interface. For this hackweek we are interested in looking at small components of this larger project that may be interesting and useful. 

## Key arctic datasets include:
[Distributed Biological Observatory (DBO)](https://www.pmel.noaa.gov/dbo/ https://arcticdata.io/catalog/data)  
[EcoFOCI](https://www.ecofoci.noaa.gov/data-links)
[Arctic Flux data from Saildrones](https://data.pmel.noaa.gov/pmel/erddap/search/index.html?page=1&itemsPerPage=1000&searchFor=Arctic+Flux+Data)
[International Arctic Buoy Programme (IABP) Data](https://iabp.apl.uw.edu/)

## Overall Tasks:
1. Identify existing data access options for the identified key datasets
2. Determine the data access needs of the GOMO program and its stakeholders
3. Evaluate data access options to determine whether they meet the needs of the GOMO program and its stakeholders
4. Investigate options for data integration into a common user interface that meets the needs of the GOMO program and its stakeholders

## HackWeek Goal:
The scope of the proposed project is quite large and long-range, but there may be a project of viable scope for the OHW by focusing on one of the key datasets. The IABP near-real-time ice buoy dataset has been partially integrated into the [PolarWatch data system](https://polarwatch.noaa.gov/about/). Data are harvested from the data provider and made available over the [PolarWatch ERDDAP](https://polarwatch.noaa.gov/erddap/tabledap/iabp_buoys.graph). PolarWatch has recently added the ability to preview in-situ datasets in its data catalog as well ([i.e. BGC ARGO](https://polarwatch.noaa.gov/catalog/insitu-bgc-argo/preview/?dataset=none&var=nitrate&time_min=2022-05-05T18:29:00Z&time_max=2022-05-19T18:29:00Z&proj=epsg3031&colorBar=KT_amp|||0|40|)), but the IABP dataset has not been added to the catalog viewer yet. 

The PolarWatch team has offered to work with us on the catalog integration of the IABP dataset during the OceanHackWeek. This will allow us to learn more about the steps involved to integrate a dataset into a catalog viewer and also provide a hands-on opportunity to begin identifing needs for GOMO data discovery, access and visualization.

## More Information about the Key Datasets:

1. Distributed Biological Observatory: Dataset are long-term observatory data that is collection of biological and physical parameters from lower to higher trophics from campaigns in areas with high productivity. 

- They have been maintaining 8 hotspot transect lines in Bering, Chukchi, and Beaufort Seas. https://www.pmel.noaa.gov/dbo/.
- Key DBO datasets are stored here: https://arcticdata.io/catalog/data <search phrase 'DBO'>
- There are also data from this long-term DBO data archive: https://data.eol.ucar.edu/dataset/dsproj?DBO

2. EcoFOCI: Ecosystem 
- Key datasets are here: https://www.ecofoci.noaa.gov/data-links
- Mooring data: https://www.pmel.noaa.gov/foci/data/data.html
- Drifter data: https://www.ecofoci.noaa.gov/drifters/efoci_drifterData.shtml
- More here: https://data.pmel.noaa.gov/pmel/erddap/info/index.html?page=1&itemsPerPage=1000
- and also at the ADC: https://arcticdata.io/catalog/data <search phrase 'EcoFOCI'>

