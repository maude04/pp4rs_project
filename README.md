# The relationship between US interest rates and public debt in developing countries

Following the Russo-Ukrainian war, the Federal Reserve Bank in the United States tightened its monetary policy. This raised the concern that higher US interest rates would increase the debt burden of developing countries through the exchange rate. Therefore, in this project, I explore the relationship between the US interest rates and the public debt in developing countries.

## Data:

1. **FRED**:
   - variable: US interest rates
   - Source: [FRED.org](https://fred.stlouisfed.org/series/FEDFUNDS)
2. **World Bank**:
   - variables: Region, income group, currency composition of debt, external debt stock (% of GNI), external debt stock (current US$), GNI per capita, GNI, exchange rate, population
   - Sources: [International debt statistics](https://databank.worldbank.org/source/international-debt-statistics#), [World development indicators](https://databank.worldbank.org/source/world-development-indicators), [Country classification income](https://blogs.worldbank.org/en/opendata/new-world-bank-group-country-classifications-income-level-fy24)
  
## Setup of the environment:

To run this project, you will have to to install the corresponding dependencies. You can either clone the environment or install the dependencies manually.

To clone [the environment](envs/env_pp4rs_project.yaml), run this command in the terminal in the folder of the project:

```bash
conda env create -f envs/env_pp4rs_project.yaml
```

To install the dependencies manually, run the following commands:

```bash
conda create --name env_pp4rs_project
conda activate env_pp4rs_project
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=env_pp4rs_project

pip install numpy
pip install pandas
pip install matplotlib
pip install scipy
pip install statsmodels
pip install openpyxl
```

## Analysis

You will find the project in [the notebook](https://github.com/maude04/pp4rs_project/blob/main/src/project_programming.ipynb)


