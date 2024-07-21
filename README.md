# Growing Economy

Analysis for the topic of `A Growing Economy`.


## Project Structure
The repository is split into the following directories:

- `data`: Contains raw data used for analysis. The provided LFS data is supplemented with additional data sources from World Bank and OECD.
- `notebooks`: Contains the research notebooks.
    - `exploratory_data_analysis.ipynb`: Exploring the provided data sources and researching different hypotheses for apporaches to a growing economy.
    - `presentation_plots.ipynb`: Creating consistently formatted plots for inclusion in the final presentation of results.
    - `survey_wordcloud.ipynb`: A wordcloud created using the qualitative survey data. I didn't actually end up using this anywhere.
- `results`: Contains output plots used for the presentation.


## Dev environment setup
We use conda to manage the virtual environment.
The following can be run from a shell terminal to install the required python packages.

```shell
conda create --name growingeconomy python=3.12
conda activate growingeconomy
pip install -r requirements.txt
```