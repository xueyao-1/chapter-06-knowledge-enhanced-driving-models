# Chapter 6: Knowledge enhanced driving models

Code, small data files, and figures accompanying this chapter. The original folder structure is preserved.

## Software

The analysis uses Jupyter notebooks and Python. Dependencies and execution paths have not yet been validated. Consult the notebooks and scripts for imports and input paths.

## Data included and omitted

Data files of at most 10 MB (10,000,000 bytes) are included. Larger files are omitted; workflows requiring those files need the original data before they can run. No replacement or sampled data has been generated.

| Omitted file | Size (MB) |
| --- | ---: |
| `Data_source_and_script/labeled_data.json` | 45.44 |

## Original chapter instructions

Input data: labeled_data_3000-6000.csv, labeled_data.json, labels.txt

Main.ipynb -- 
- Extract features of labels and durations. 
- Visualize probability of pattern transition and duration
- Data preparation to encode pattern transition and duration
- Main model training: 
	Knowledge-enhanced model: KE(P+D)-ALSTM, KE(P+D)-LSTM, KE(P+D)Transformer, KE(P)-ALSTM, KE(D)-ALSTM,
	Baseline models: LSTM, ALSTM
- Loss balancing: test of the balance of two prediction tasks
- Sensitivity analysis: to find the optimal lambda_1 and lambda_2
- Sensitivity analysis: to find the optimal hidden size and layers number
