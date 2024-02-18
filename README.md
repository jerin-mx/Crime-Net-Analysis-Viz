# Net-Crime-Viz

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
Highlighted individuals within the network include Daniel Serero, the mastermind, Pierre Perlini, Serero's principal lieutenant, investors and transporters like Alain and Gérard Levy, and other crucial figures playing diverse roles within the network.

## Analysis
This project undertakes the analysis of time-varying network data to map out the structure, dynamics, and evolution of the criminal network. By leveraging graph visualization and centrality measures, we reveal the adaptation strategies of network players in response to law enforcement interventions.

## Research Paper

For further reading and a deeper understanding of the methodologies used, refer to the research paper available at [Modeling Verdict Outcomes Using Social Network Measures](https://www.researchgate.net/publication/292304919_Modeling_Verdict_Outcomes_Using_Social_Network_Measures_The_Watergate_and_Caviar_Network_Cases).

## Usage
Data files (e.g.,'phase1.csv', 'phase2.csv', ...) contain wiretap correspondences between network players, identified by unique ids. The project includes scripts to convert these ids to strings (e.g., 'n1', 'n2', ...) for better readability and creates network graphs for each phase, stored in the 'G' dictionary.
