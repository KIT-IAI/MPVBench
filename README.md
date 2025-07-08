<p float="left">
    <img src="data/img/icon_kit.png" width="10%" hspace="20"/> 
</p>

[![Python](https://img.shields.io/badge/Python-3.9.18-blue?logo=python)](https://www.python.org/downloads/release/python-3918/)
[![License](https://img.shields.io/badge/License-MIT-green?logo=opensource)](./LICENSE)
[![Code Style](https://img.shields.io/badge/Code%20Style-black-000000.svg?logo=python)](https://github.com/psf/black)
[![](https://img.shields.io/badge/Contact-goekhan.demirel%40kit.edu-yellow?label=Contact)](goekhan.demirel@kit.edu)
[![DOI](https://img.shields.io/badge/DOI-10.1007/978-3-031-74741-0_16-orange?logo=doi)](https://doi.org/10.1007/978-3-031-74741-0_16)

![MPVBenchLogo](data/img/00MPVBench_logo.svg)

<h1 align="center">Impact and Integration of Mini Photovoltaic Systems on Electric Power Distribution Grids</h1>

**⚠️ Note**: *Last update on 08.07.2025*


This **MPVBench** repository provides supplementary materials for the paper [Impact and Integration of Mini Photovoltaic Systems on Electric Power Distribution Grids](https://link.springer.com/chapter/10.1007/978-3-031-74741-0_16). This repository provides open-source, real-time measured data from five Mini Photovoltaic (MPV) or Balcony Power Plants systems located in Karlsruhe and Pforzheim.

## Data Types
The repository provides data on 15-minute power production (W) and temperature (K) and is updated monthly.

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
│   ├── p_watt.csv
│   └── t_celsius.csv
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
If you use this framework in your research, please consider citing our paper &#128221; and giving the repository a star &#11088;:
</p>


#### BibTeX format
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
