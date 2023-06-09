# RMI Metals Emissions Reporting Guidance
This repository holds RMI's Steel and Aluminum Emissions Reporting Guidance, along with licensing and related documents.

RMI's Steel Emissions Reporting Guidance consists of accounting guidance, in the form of PDF file, as well as a Pathfinder Network Data Model Extension The accounting guidance was launched in September of 2022--you can read the blog post [here](https://rmi.org/knowing-the-emissions-of-your-steel-supply-chain/) and press release [here](https://rmi.org/press-release/rmi-releases-guidance-to-cut-steel-industrys-climate-threat/).

RMI's Aluminum Emissions Reporting Guidance

## Product Level Accounting Guidance
The steel accounting guidance can be found [here:](https://github.com/RMI/steel-guidance/blob/main/RMI%20Horizon%20Zero%20Steel%20Guidance.pdf)

This guidance was authored by [RMI](https://rmi.org/) in collaboration with the [World Business Council for Sustainable Development (WBCSD)](https://www.wbcsd.org/) and its [Automotive Partnership for Carbon Transparency (A-PACT)](https://www.wbcsd.org/Pathways/Transport-Mobility/News/Leading-manufacturers-support-move-towards-better-emissions-measurement-for-the-automotive-industry) initiative.

### Emissions Reporting Requirements
There are four key requirements for reporting steel sector emissions using this Steel Emissions Reporting Guidance:

#### 1. Product level
Emissions must be reported at the product level for an individual site.

#### 2. Fixed boundary
All emissions from a set of processes must be reported irrespective of whether the company has
ownership or control of these processes.

#### 3. Supply chain transparency
Additional context about the scrap-based inputs, total carbon emissions intensity position relative to the 1.5C trajectory and abatement technology (refer to section 2.4 of the [accounting guidance](https://github.com/RMI/steel-guidance/blob/main/RMI%20Horizon%20Zero%20Steel%20Guidance.pdf)) to assist in understanding the overall emissions footprint.

#### 4. Data source
Emissions disclosures must include the fraction of the emissions footprint that is based on primary
data (refer to section 3.5)20 and separately report any emissions credits.

### Fixed System Boundary
The fixed system boundary defines all the process steps from which emissions need to be reported irrespective of the steel companies’ ownership structure. This approach solves two key issues:

#### Emissions disclosure at the corporate level will vary depending on the degree of vertical integration
#### Scope 1, 2, and 3 will likely become more fluid overtime, further limiting comparability

For more information on the Fixed System Boundary, see section 2.2 of the [accounting guidance](https://github.com/RMI/steel-guidance/blob/main/RMI%20Horizon%20Zero%20Steel%20Guidance.pdf)

## Pathfinder Network Data Model Extension
In addition to the Product Level Accounting Guidance, this repository contains supporting documents for a [Pathfinder Network](https://www.carbon-transparency.com/) Data Model Extension for Steel, which is designed to be used in concert with RMI's Steel Emissions Reporting Guidance.

The Pathfinder Data Model is designed to enable the use of machine-readable sharing of product level information. Extensions to the model allow for sector specific information to be added to the data model. sTechnical guidance on the Pathfinder Network data model can be found [here.](https://wbcsd.github.io/data-exchange-protocol/v2/)

### Key Terms
Some key terms for understanding the data model extension:

#### Low Carbon or Abatement Tech
  A qualitative label of the techology used to reduce emissions in the steel and aluminum supply chains. For more information please refer to section 2.4 of the [steel accounting guidance.](https://github.com/RMI/steel-guidance/blob/main/RMI%20Horizon%20Zero%20Steel%20Guidance.pdf)
  
#### Mine to Smelter
  The ore-based or mine-to-smelter portion of aluminum production. For more information, please refer Secs 2.3 and 3.2 of RMI's Aluminum Guidance.
  
#### Credits
  Avoided emissions outside the fixed systems boundary. Credits are required to be seperately reported from the total emissions intensity.
  
#### Process Names
  Discrete processes used in the production of steel. E.g. hot rolling, briquetting, casting. For more information see Sec 2.2 Fixed Boundary of RMI's [Steel Emissions Reporting Guidance.](https://github.com/RMI/steel-guidance/blob/main/RMI%20Horizon%20Zero%20Steel%20Guidance.pdf)

#### Process Steps
  A grouping of Process Names along with their total emissions intensity, recycled content, exports, credits, and other related metadata. See [4.10. Data Type ProcessSteps](https://github.com/RMI/metals-guidance/blob/main/specs/technical_specification.md#4.10.-data-type-process-steps).

#### Process Groups
  A grouping of Process Steps along with company information. See [4.8. Data Type ProcessGroups](https://github.com/RMI/metals-guidance/blob/main/specs/technical_specification.md#4.8.-data-type-processgroups).

### Techical Guidance
For full techical guidance on RMI's Metals Data Model Extension, see [here.](https://github.com/RMI/metals-guidance/blob/main/specs/technical_specification.md)

### Sample and Schema Files
A sample file of the data model extension can be found [here.](https://github.com/RMI/metals-guidance/blob/main/samples/metals_extension.json) Note: this sample file includes the full Pathfinder Data Model file as well as RMI's Metals Extension.

A json schema file for the data model extension can be found [here.](https://github.com/RMI/metals-guidance/blob/main/specs/metals_json_schema.json)

## Contacts

### RMI
For questions please contact ghgtransparency@rmi.org
