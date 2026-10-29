
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



