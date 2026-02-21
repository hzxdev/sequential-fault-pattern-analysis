# Sequential Fault Pattern Analysis

## Overview
This project focuses on identifying temporal patterns in fault data with Sequential Pattern Mining (SPM) and Sequential Rule Mining (SRM) using [SPMF](https://www.philippe-fournier-viger.com/spmf/), an open source data mining library. By analyzing fault sequences, we can identify precursor events that lead to system failures which allow us to make proactive interventions.

## Dataset
Source: Industrial faults.mat dataset.

Structure: 10,000 sequences of machine event logs, where each character represents a specific fault type or system state.


## Libraries
Scipy (for .mat handling), Pandas, PrefixSpan

## Algorithms Implemented

- PrefixSpan

- GSP

- SPADE

- RuleGrowth

- CMRules

## Performance of Algorithms

| Algorithm | Type | Execution Time (s) |
| :--- | :--- | :--- |
| **RuleGrowth** | Rule Mining | **1.703** |
| **CMRules** | Rule Mining | 2.226 |
| **SPADE** | Pattern Mining | **0,385** |
| **GSP** | Pattern Mining | 0,697 |
| **PrefixSpan** | Pattern Mining | 2.739 |

