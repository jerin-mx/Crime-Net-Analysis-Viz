# CAVIAR Investigation Network Visualisation & Analysis

## Overview
Analysis of a 2-year criminal network with 101 players, disturbed by police actions. Utilizes graph visualization and centrality measures to identify key figures and trends. Highlights the effectiveness of degree centrality in revealing vital network players and their evolving roles.

## Data Source
The dataset is housed in the CAVIAR directory of a comprehensive data archive, representing 11 distinct phases of wiretap data collected during the operation from 1994 to 1996. This operation was a collaborative effort between the Montréal police and the Royal Canadian Mounted Police of Canada.

## Seizures Summary
The following table provides a concise overview of the seizures made throughout the investigation, including the phase, amount in USD, and the specifics of each seizure:

| Phase | Seizures | Amount (USD) | Details                        |
|-------|----------|--------------|--------------------------------|
| 4     | 1        | 2,500,000    | 300 kg of marijuana            |
| 6     | 3        | 1,300,000    | 30 kg marijuana + 2 kg cocaine |
| 7     | 1        | 3,500,000    | 401 kg of marijuana            |
| 8     | 1        | 360,000      | 9 kg of cocaine                |
| 9     | 2        | 4,300,000    | 2 kg cocaine + 500 kg marijuana|
| 10    | 1        | 18,700,000   | 2200 kg of marijuana           |
| 11    | 2        | 1,300,000    | 23 kg of cocaine               |

## Network Composition
The investigation's focus was on a network comprising 110 players, including traffickers and various non-traffickers like financial investors and importation business owners. Initially targeting Daniel Serero, the network's alleged mastermind, the project traces the network's shift in operations and key player roles over time.

## Key Players

The investigation identified several critical roles within the criminal network, each contributing to its operations in distinct ways:

- **Daniel Serero (n1):** Mastermind of the network.
- **Pierre Perlini (n3):** 
  - Principal lieutenant of Serero, executing his instructions.
- **Alain (n83) and Gérard (n86) Levy:** 
  - Investors and transporters of money.
- **Wallace Lee (n85):** 
  - Manages financial affairs as the network's accountant.
- **Gaspard Lino (n6):** 
  - Broker located in Spain.
- **Samir Rabbat (n11):** 
  - Provider in Morocco.
- **Lee Gilbert (n88):** 
  - Trusted financial manager for Wallace Lee, later became an informer.
- **Beverly Ashton (n106):** 
  - Spouse of Lino, involved in transporting money and documents.
- **Antonio Iannacci (n89):** 
  - Investor.
- **Mohammed Echouafni (n84):** 
  - Moroccan investor.
- **Richard Gleeson (n5), Bruno de Quinzio (n8), Gabrielle Casale (n76):** 
  - Tasked with recuperating marijuana.
- **Roderik Janouska (n77):** 
  - Individual with airport contacts.
- **Patrick Lee (n87):** 
  - Investor.
- **Salvatore Panetta (n82):** 
  - Manager of transport arrangements.
- **Steve Cunha (n96):** 
  - Transport manager and owner of a legitimate import company, later an informer.
- **Ernesto Morales (n12):** 
  - Principal organizer of cocaine import, acting as an intermediary between Colombians and the Serero organization.
- **Oscar Nieri (n17):** 
  - Handyman for Morales.
- **Richard Brebner (n80):** 
  - Transported cocaine from the US to Montréal.
- **Ricardo Negrinotti (n33):** 
  - Took possession of cocaine in the US to hand off to Brebner.
- **Johnny Pacheco (n16):** 
  - Cocaine provider.

## Analysis
This project undertakes the analysis of time-varying network data to map out the structure, dynamics, and evolution of the criminal network. By leveraging graph visualization and centrality measures, we reveal the adaptation strategies of network players in response to law enforcement interventions.

## Research Paper

For further reading and a deeper understanding of the methodologies used, refer to the research paper available at [Modeling Verdict Outcomes Using Social Network Measures](https://www.researchgate.net/publication/292304919_Modeling_Verdict_Outcomes_Using_Social_Network_Measures_The_Watergate_and_Caviar_Network_Cases).

## Usage
Data files (e.g.,'phase1.csv', 'phase2.csv', ...) contain wiretap correspondences between network players, identified by unique ids. The project includes scripts to convert these ids to strings (e.g., 'n1', 'n2', ...) for better readability and creates network graphs for each phase, stored in the 'G' dictionary.
