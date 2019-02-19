# Master Thesis Raw Data Repository
This repository contains all the data collected and used for the master thesis of Muhammed Akbulut for the degree of Master of Engineering.

## Software quality metrics and software best practices metrics
All these csv files contain the following columns
```
    'analyser_loc',
    'analyser_cloc',
    'analyser_cyclomatic_complexity',
    'analyser_duplication',
    'analyser_unit_size',
    'sniffer_errors',
    'analyser_forks',
    'analyser_contributor',
```
### calisthenics
Contains per repository data collected about software quality metrics and violations of calisthenics. This column is named `sniffer_errors`.
### solid
Contains per repository data collected about software quality metrics and violations of calisthenics. This column is named `sniffer_errors`.

## popular php repositories
https://api.github.com/search/repositories?q=language:PHP+stars%3A%3E0&sort=stars&per_page=100

## test coverage data
Contains all the data where available about test coverage with PHPUnit

## test coverage raw data
Contains all the raw text reports from PHPUnit about a certain repository:tag
