
# PIER
Perspectives on Indian Energy based on Rumi (PIER), is an Indian energy systems model built on the Rumi modelling platform. Version 2 of PIER, with a time horizon of FY2040-41, features detailed bottom-up modelling of energy demand from three sectors (residential, transport and industry), newer supply options such as offshore wind and green hydrogen, and features such as blending of ethanol with Motor Spirit. 

PIER 2 will be released in phases - one sector at a time. This release consists of the demand model, and the supply model will be made public in a future release. Details about the various releases of Rumi and PIER can be found at https://energy.prayaspune.org/our-work/data-model-and-tool/rumi-pier
 
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
PIER is an energy systems model for India, that estimates demand and cost-optimal supply options to meet the demand up to 2040-41. Demand is estimated separately for five different sectors: residential, transport, industry, agriculture and "others". Demand is estimated for each energy carrier and for each sector at as fine a granularity as possible. Thus, residential demand is estimated for carriers such as electricity, biomass (solid fuels) and LPG separately for urban and rural households in 25 states in India, with electricity demand being estimated for each hour of a representative day for each month of each year of the period modelled. Transport energy demand is estimated for each transport fuel (such as Motor Spirit and High Speed Diesel) and for each state, with electricity demand for transport also being estimated at the same temporal granularity as the residential sector. 

This release only includes the demand estimation model of PIER 2. The supply model will be updated in a subsequent release.

Various scenarios are modelled to reflect different possible future pathways, with the input assumptions and values changing across the scenarios. 

## PIER folder structure

PIER follows the folder structure as requried by Rumi. Detailed documentation of Rumi is available at https://github.com/prayas-energy/Rumi `Docs.zip` under the latest release tag.

## PIER scenario data

The scenarios are described in the Scenarios/demand-scenarios-description.pdf.

[`Docs/Parameters & Source file-map.xlsx`](Docs/Parameters%20%26%20Source%20file-map.xlsx) is the starting point in PIER to understand the data being released with PIER. It lists the various 'source' files (xlsx) which are used to build the actual input data for the model. It also lists the various 'parameter' files (csv) that form the actual input data used in any scenario. 

The 'parameter' files that form the PIER model are generated in source files that contain detailed documentation on how parameter data is constructed in that source file, and all the relevant data sources, assumptions and methodology used. The source files are found under `Common/Source`, `Demand/Source` and `Supply/Source` of the respective scenario, and the parameter files are found under `Common/Parameters`, `Demand/Parameters` and `Supply/Parameters`.

The 'Parameters & Source file-map.xlsx' and the source files will be checked in a subsequent release.

## PIER outputs

The outputs of each of the scenario runs are created under the corresponding `Scenarios/<scenario_name>/Demand/Output` folder.

## Version 
PIER v2.0.0 is in sync with Rumi v2.0.0.

<a href="https://github.com/prayas-energy/Rumi"><img src="https://github.com/prayas-energy/Rumi/blob/main/Docs/graphics/Rumi-Logo-75dpi.png" width="200"></a>

Rumi is available at https://github.com/prayas-energy/Rumi 


## Contact 
Contact Prayas (Energy Group) at energy.model@prayaspune.org for any queries regarding PIER and Rumi.
