<p float="left">
    <img src="data/img/icon_kit.png" width="10%" hspace="20"/> 
</p>

[![Python](https://img.shields.io/badge/Python-3.9.18-blue?logo=python)](https://www.python.org/downloads/release/python-3918/)
[![License](https://img.shields.io/badge/License-MIT-green?logo=opensource)](./LICENSE)
[![Code Style](https://img.shields.io/badge/Code%20Style-black-000000.svg?logo=python)](https://github.com/psf/black)
[![](https://img.shields.io/badge/Contact-goekhan.demirel%40kit.edu-yellow?label=Contact)](goekhan.demirel@kit.edu)
[![DOI](https://img.shields.io/badge/DOI-10.1007%2F9783031.74741016-orange?logo=doi)](https://doi.org/10.1007/978-3-031-74741-0_16)

![MPVBenchLogo](data/img/00MPVBench_logo.svg)

<h1 align="center">Impact and Integration of Mini Photovoltaic Systems on Electric Power Distribution Grids</h1>

**⚠️ Note\***: _Last update on 08.11.2026 — the dataset now covers the two full years 2024 and 2025._

This **MPVBench** repository provides supplementary materials for the paper [Impact and Integration of Mini Photovoltaic Systems on Electric Power Distribution Grids](https://link.springer.com/chapter/10.1007/978-3-031-74741-0_16). This repository provides open-source, real-time measured data from **five** Mini Photovoltaic (MPV) or Balcony Power Plant systems located in Karlsruhe and Pforzheim.

## Dataset at a Glance

| Item | Value |
|---|---|
| Number of MPV systems (measurement units) | **5** (five independent power meters, one data column each) |
| Profiles / columns | `1a`, `1b`, `1c`, `2a`, `2b` |
| Pforzheim (Enzkreis) | 4 systems: 1a, 1b, 2a, 2b |
| Karlsruhe | 1 system: 1c |
| Measurement period of the current release | 2024-01-01 to 2025-12-31 (two full years, 731 days) |
| Resolution | 5 min (210 528 rows) and 15 min (70 176 rows) |
| Measured quantities | AC power (W), device temperature (°C) |
| Rated inverter output per system | 600 W (Hoymiles HMS-600-2T), two PV modules each |

The number of systems is given by the data itself: every row of the raw measurements carries the MAC address of its power meter, and exactly five distinct MAC addresses occur in the whole dataset. There is **no sixth unit** in the data.

## Data Types

The repository provides power production (W) and temperature (°C) measurements at 5-minute and 15-minute resolution.

## Dataset Coverage

- **First version (2023-08-04 to 2024-07-31):** released with the [Impact and Integration of Mini Photovoltaic Systems on Electric Power Distribution Grids](https://doi.org/10.1007/978-3-031-74741-0_16).
- **Extension to the full year 2024:** released with the [PIDE: Photovoltaic integration dynamics and efficiency for autonomous control on power distribution grids](https://doi.org/10.1186/s42162-025-00489-6).
- **Current version\* (2024-01-01 to 2025-12-31):** uploaded for the dissertation, covering the two full years **2024 and 2025** (five MPV profiles: 1a, 1b, 1c, 2a, 2b).
  - The release is tagged `v2.0.0` in this repository.

## Repository Structure

<details>
  <summary>Click to expand/collapse</summary>

```plaintext
MPVBench/
├── data/
│   ├── img/
│   ├── 00_ka_mpv_metadata.md
│   ├── 00_pf_mpv_metadata.md
│   ├── 01a_mpv_metadata.md
│   ├── 01b_mpv_metadata.md
│   ├── 01c_mpv_metadata.md
│   ├── 02a_mpv_metadata.md
│   ├── 02b_mpv_metadata.md
│   ├── p_watt_5min.csv
│   ├── p_watt_15min.csv
│   ├── t_celsius_5min.csv
│   └── t_celsius_15min.csv
├── LICENSE
├── MPVBench_Tutorial.ipynb
├── README.md
└── requirements.txt
```

The structure of the repository is as follows:

- CSV data files (e.g., [p_watt_5min.csv](data/p_watt_5min.csv), [p_watt_15min.csv](data/p_watt_15min.csv), [t_celsius_5min.csv](data/t_celsius_5min.csv), [t_celsius_15min.csv](data/t_celsius_15min.csv)).
- Metadata files for technical specifications (e.g., [01a_mpv_metadata.md](data/01a_mpv_metadata.md)).
- Jupyter notebooks for tutorial ([MPVBench_Tutorial.ipynb](MPVBench_Tutorial.ipynb)).

<img src="data/img/05MPVs_Location_map.svg" alt="MPVBenchmarkMAP" style="width:30%;">

</details>

## How to Use

1. Clone the repository:
   ```bash
   git clone git@github.com:KIT-IAI/MPVBench.git
   pip install -r requirements.txt
   ```

<h2>Citation &#128221;</h2>
<p>
If you use this framework in your research, please consider citing our papers &#128221; and giving the repository a star &#11088;. Please cite the first work <b>[1]</b>, as it represents the full dataset; the second work <b>[2]</b> only covers a subset of the data:
</p>

#### BibTeX format

**[1]** Full dataset (2024-01-01 to 2025-12-31):

```tex
@Article{Demirel_PIDE_2025,
    author = {Demirel, Gökhan and Fernengel, Natascha and Grafenhorst, Simon and Förderer, Kevin and Hagenmeyer, Veit},
    title = {{PIDE}: Photovoltaic integration dynamics and efficiency for autonomous control on power distribution grids},
    journal = {Energy Informatics},
    year = {2025},
    volume = {8},
    number = {1},
    publisher = {Springer Nature},
    issn = {2520-8942},
    doi = {10.1186/s42162-025-00489-6}
}
```

**[2]** Subset of the data (2023-08-04 to 2024-07-31):

```tex
@InProceedings{Demirel_MPV_2024,
    author = {Demirel, Gökhan and Grafenhorst, Simon and Förderer, Kevin and Hagenmeyer, Veit},
    editor = {Jørgensen, Bo Nørregaard and Ma, Zheng Grace and Wijaya, Fransisco Danang and Irnawan, Roni and Sarjiya, Sarjiya},
    title = {Impact and Integration of Mini Photovoltaic Systems on Electric Power Distribution Grids},
    booktitle = {Energy Informatics},
    year = {2025},
    publisher = {Springer Nature Switzerland},
    address = {Switzerland Cham},
    pages = {247--265},
    isbn = {978-3-031-74741-0}
}
```

## License

This code is licensed under the [MIT License](LICENSE).
