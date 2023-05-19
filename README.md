# HostBSGSNe: Planning IFU observations of Hosts of 1987A-like SNe arising from Blue Supergiants

[![Python 3.10.5](https://img.shields.io/badge/python-3.10.5-blue)](https://www.python.org/downloads/release/python-395/)
[![License](https://img.shields.io/github/license/sPaMFouR/HostBSGSNe)](https://github.com/sPaMFouR/HostBSGSNe)

The repository houses material for planning IFU observations of host environments of 1987A-like SNe arising from Blue Supergiants.

The code just began development in Feb 2023.

Global Requirements:

- os
- numpy
- urllib
- pandas
- astropy
- astroquery
- matplotlib

## 1) FormatSample.ipynb
Required File(s): [`data/AMUSINGSample.csv`]<br />
Output File(s): [`data/AMUSING_CCSNe.dat`]<br />

- 'FormatSample.ipynb' is a jupyter-notebook for filtering out observations performed by AMUSING survey on host environments of CCSNe.

## 2) PlanningIFU.ipynb
Required File(s): [`TargetList.dat`]<br />
Output File(s): [`findingchart/PlanTarget.png`]<br />

Descriptipn:
- 'PlanningIFU.ipynb' is a jupyter-notebook for planning IFU observations and plot finding charts for targets superposed with the IFU pointing.
