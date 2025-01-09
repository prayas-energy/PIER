
# PIER
Perspectives on Indian Energy based on Rumi (PIER), is an Indian energy systems model built on the Rumi modelling platform. Version 2 of PIER, with a time horizon of FY2040-41, features detailed bottom-up modelling of energy demand from three sectors (residential, transport and industry), newer supply options such as offshore wind and green hydrogen, and features such as blending of ethanol with Motor Spirit.

# PIER Releases
Henceforth, PIER model releases will be made on Zenodo at https://doi.org/10.5281/zenodo.14603083.

PIER 2 will be released in phases - one sector at a time. The demand model has been released at the above Zenodo link, and the supply model will subsequently be made public. Details about the various releases of Rumi and PIER can be found at https://energy.prayaspune.org/our-work/data-model-and-tool/rumi-pier
 
# LICENSE-CC-BY-4.0

UNLESS OTHERWISE NOTED, THE CONTENTS OF THIS DIRECTORY ARE LICENSED UNDER THE CREATIVE COMMONS ATTRIBUTION 4.0 INTERNATIONAL LICENSE.

<a href="#license-cc-by-40"><img src="https://i.creativecommons.org/l/by/4.0/88x31.png" width="88"></a> 


## License Summary of CC-BY 4.0 International

*This section is a human-readable summary of (and not a substitute for) the full license available at https://creativecommons.org/licenses/by/4.0/legalcode*

### You are free to:

* **Share** : copy and redistribute the material in any medium or format
* **Adapt** : remix, transform, and build upon the material for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the license terms.

### Under the following terms:

* <a href="#license-summary-of-cc-by-40-international"><img src="https://creativecommons.org/images/deed/by.png" width="50"></a> **Attribution** : You must give **appropriate credit**, provide **a link to the license**, and **indicate if changes were made**. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

* **No additional restrictions** : You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

### Notices:

* You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable **exception or limitation**.

* No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as **publicity, privacy, or moral rights** may limit how you use the material.

*Please see the [LICENSE](/LICENSE) file for all the terms.*

# Description of PIER 
PIER is an energy systems model for India, that estimates demand and cost-optimal supply options to meet the demand up to 2040-41. Demand is estimated separately for five different sectors: residential, transport, industry, agriculture and "others". Demand is estimated for each energy carrier and for each sector at as fine a granularity as possible. Thus, residential demand is estimated for carriers such as electricity, biomass (solid fuels) and LPG separately for urban and rural households in 25 states in India, with electricity demand being estimated for each hour of a representative day for each month of each year of the period modelled. Transport energy demand is estimated for each transport fuel (such as Motor Spirit and High Speed Diesel) and for each state, with electricity demand for transport also being estimated at the same temporal granularity as the residential sector.  Industrial energy demand for fuels (such as coking coal, thermal coal, natural gas, petcoke etc) is estimated at the national level with electricity demand being estimated at the state level at the same temporal granularity as the residential sector.  Industrial energy demand is estimated in a detailed way for the steel, cement and aluminium industries, which are the top energy consuming industries.

The supply module of PIER models available energy supply options for the various energy carriers, based on which Rumi picks the best options to meet total demand for each energy carrier. The supply options for primary carriers (such as coal, crude oil and natural gas) include domestic and imported variants of the carrier. For derived carriers (such as electricity, petroleum products and hydrogen), the options range across various technologies that can produce these carriers (such as coal, gas, solar, wind etc. for electricity generation; and refining for petroleum products). 

Various scenarios are modelled to reflect different possible future pathways, with the input assumptions and values changing across the scenarios. 

## PIER scenarios

There are 3 overall scenarios in PIER Version 2:
1. Reference (1_REF): This is a combination of the sector-specific reference scenarios, and represents what is likely to happen in the future based on past and likely future trends.
2. 'Vikasit Bharat’ (2_Vikasit): This scenario can represent the equivalent of a ‘sustainable development’ scenario. It reflects the aspirations of a ‘developed India’ by 2047 (FY48) announced by the Government of India. We assume that this also means a more equitable development, with greater focus on sustainability.
3. ‘Vichalit Bharat’ (3_Vichalit): This scenario is a counter-point to Vikasit Bharat, and represents a scenario in which development is a bit more haphazard. Economic growth is lower than Reference, it is less equitable, and it is also less environmentally sustainable due to lower investments in efficiency and new technologies.

More details are available in [`Scenarios/demand-scenarios-description.pdf`](Scenarios/demand-scenarios-description.pdf)

## PIER folder structure

PIER follows the folder structure as requried by Rumi. Detailed documentation of Rumi is available at https://github.com/prayas-energy/Rumi `Docs.zip` under the latest release tag.

The PIER folder structure consists of the model input data (csvs) in the 'Parameters' folders and supporting documentation in the form of 'source' workbooks (xlsx) in the 'Source' folders, which are used to build the model input data. At the top level, there is a folder named 'Default Data' which typically consists of model data and source workbooks for the default scenario (in this case, 1_REF).  Each source workbook has detailed documentation on how parameter data is constructed in that source file, and includes all the relevant data sources, assumptions and methodology used. The source files are found under `Common/Source`, `Demand/Source` and `Supply/Source` of the respective scenario, and the parameter files are found under `Common/Parameters`, `Demand/Parameters` and `Supply/Parameters`. 

## PIER outputs

The outputs of each of the scenarios are provided under the corresponding `Demand/Outputs` and `Supply/Outputs` directories of the respective scenario folder under the 'Scenarios' directory at the root level. 

## Version 
PIER v2.0 is in sync with Rumi v2.0.

<a href="https://github.com/prayas-energy/Rumi"><img src="https://github.com/prayas-energy/Rumi/blob/main/Docs/graphics/Rumi-Logo-75dpi.png" width="200"></a>

Rumi is available at https://github.com/prayas-energy/Rumi 


## Contact 
Contact Prayas (Energy Group) at energy.model@prayaspune.org for any queries regarding PIER and Rumi.
