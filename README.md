
# Happiness Analysis

This repository contains an analysis of global happiness scores, utilizing data from the World Happiness Report. The goal is to understand the factors that contribute to happiness in different countries.

## Project Overview

The analysis focuses on various indicators such as GDP per capita, social support, healthy life expectancy, freedom to make life choices, generosity, and perceptions of corruption, as well as their impact on overall happiness scores.

## Table of Contents

- [Data Overview](#data-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Data Overview

The dataset includes the following columns:
- **Rank**: The rank of the country based on happiness score.
- **Country**: The name of the country.
- **Happiness score**: The overall happiness score.
- **Whisker-high**: The upper end of the 95% confidence interval for the happiness score.
- **Whisker-low**: The lower end of the 95% confidence interval for the happiness score.
- **Dystopia (1.83) + residual**: The baseline happiness score.
- **Explained by: GDP per capita**: Contribution of GDP to happiness score.
- **Explained by: Social support**: Contribution of social support to happiness score.
- **Explained by: Healthy life expectancy**: Contribution of healthy life expectancy to happiness score.
- **Explained by: Freedom to make life choices**: Contribution of freedom to happiness score.
- **Explained by: Generosity**: Contribution of generosity to happiness score.
- **Explained by: Perceptions of corruption**: Contribution of perceptions of corruption to happiness score.

## Data Example

The following table summarizes the happiness scores and contributing factors for selected countries:

| RANK | Country                         | Happiness score | Whisker-high | Whisker-low | Dystopia (1.83) + residual | Explained by: GDP per capita | Explained by: Social support | Explained by: Healthy life expectancy | Explained by: Freedom to make life choices | Explained by: Generosity | Explained by: Perceptions of corruption |
|------|---------------------------------|------------------|--------------|--------------|-----------------------------|------------------------------|-----------------------------|-----------------------------------------|-----------------------------------------------|-------------------------|-----------------------------------------|
| 5    | Netherlands                     | 7.415            | 7.471        | 7.359        | 2.137                       | 1.945                        | 1.206                       | 0.787                                   | 0.651                                         | 0.271                   | 0.419                                   |
| 16   | United States                   | 6.977            | 7.065        | 6.888        | 2.214                       | 1.982                        | 1.182                       | 0.628                                   | 0.574                                         | 0.220                   | 0.177                                   |
| 19   | Belgium                         | 6.805            | 6.890        | 6.720        | 2.283                       | 1.907                        | 1.106                       | 0.764                                   | 0.492                                         | 0.049                   | 0.204                                   |
| 20   | France                          | 6.687            | 6.758        | 6.615        | 1.895                       | 1.863                        | 1.219                       | 0.808                                   | 0.567                                         | 0.070                   | 0.266                                   |
| 26   | Taiwan Province of China       | 6.512            | 6.596        | 6.429        | 2.002                       | 1.897                        | 1.095                       | 0.733                                   | 0.542                                         | 0.075                   | 0.168                                   |
| 29   | Spain                           | 6.476            | 6.560        | 6.392        | 1.893                       | 1.808                        | 1.211                       | 0.808                                   | 0.505                                         | 0.101                   | 0.149                                   |
| 38   | Brazil                          | 6.293            | 6.384        | 6.202        | 2.361                       | 1.462                        | 1.044                       | 0.615                                   | 0.546                                         | 0.131                   | 0.134                                   |
| 43   | Serbia                          | 6.178            | 6.294        | 6.062        | 2.031                       | 1.550                        | 1.086                       | 0.658                                   | 0.546                                         | 0.219                   | 0.088                                   |
| 57   | Argentina                      | 5.967            | 6.090        | 5.844        | 1.891                       | 1.592                        | 1.102                       | 0.662                                   | 0.555                                         | 0.081                   | 0.085                                   |

## Installation

To install the necessary libraries, run the following command:

```bash
pip install -r requirements.txt
```

## Usage

To run the analysis, execute the following command:

```bash
python analysis.py
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
