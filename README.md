
# PIER
Perspectives on Indian Energy based on Rumi (PIER), is an Indian energy systems model with a time horizon of FY2030-31 built on the Rumi modelling platform. 
A detailed report on PIER, including data-sources and assumptions is available at https://www.prayaspune.org/peg/publications/item/512. 


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
## Scenarios and Sensitivity runs 
PIER models three scenarios: 
1. Reference (`S1_Ref`)
2. Pessimistic Recovery Scenario (`S2_PRS`) and
3. Optimistic Recovery Scenario (`S3_ORS`) 

Apart from these, PIER includes the following sensitivity runs:
1.	Higher and lower trigger and reference temperatures for space cooling (`Sens01_TrigRefTempHi` & `Sens01_TrigRefTempLo`)
2.	Lower feasibility of solar and wind capacity addition (`Sens02_LowerSolarWindAddn`) 
3.	Equal feasibility of solar and wind capacity addition (`Sens02_EqualSolarWindAddn`)
4.	Different trajectories of renewable and fossil-fuel costs (`Sens03_Costs_HighRELowFossil` & `Sens03_Costs_LowREHighFossil`)
5.	Higher and lower costs of storage (`Sens04_Costs_StorageCapexHigh` & `Sens04_Costs_StorageCapexLow`)
6.	Maximum appliance efficiency in the horizon year (`Sens05_ApplEfficiencyHi`)

## PIER folder structure
PIER follows the folder structure as requried by Rumi. Detailed documentation of Rumi is available at https://github.com/prayas-energy/Rumi `Docs.zip` under the latest release tag.

## PIER scenario data

[`Docs/Parameters & Source file-map.xlsx`](Docs/Parameters%20%26%20Source%20file-map.xlsx) is the starting point in PIER to understand the data being released with PIER. It lists the various 'source' files (xlsx) which are used to build the actual input data for the model. It also lists the various 'parameter' files (csv) that form the actual input data used in any scenario. Each source file has detailed documentation on how parameter data is constructed in that source file, and includes all the relevant data sources, assumptions and methodology used. The source files are found under `Common/Source`, `Demand/Source` and `Supply/Source` of the respective scenario or sensitivity run, and the parameter files are found under `Common/Parameters`, `Demand/Parameters` and `Supply/Parameters`. 

## PIER outputs

The outputs of each of the scenarios and sensitivity analyses are provided under the corresponding `Demand/Outputs` and `Supply/Outputs` directories of the scenario or sensitivity run. 

## Version 
PIER v1.1.0 is in sync with Rumi v1.1.0.

<a href="https://github.com/prayas-energy/Rumi"><img src="https://github.com/prayas-energy/Rumi/blob/main/Docs/graphics/Rumi-Logo-75dpi.png" width="200"></a>

Rumi is available at https://github.com/prayas-energy/Rumi 


## Contact 
Contact Prayas (Energy Group) at energy.model@prayaspune.org for any queries regarding PIER and Rumi.
