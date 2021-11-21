# Document-MultiLabel-Classification
Multilabel classification on Reuters-21578 Dataset on 5 labels (unbalanced)  using various models
relevent labels = 
## Class balance :

## Results :

Model | Total F1 | earn F1 | acq F1 | interest F1 | ship F1 | money-fx | Time
------------ |------------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- 
| SVM | 95.47 |	98.48 |	97.98 |	82.73	| 91.46	| 86.65	| 15.91
| SVM_balanced | 96.5	|	98.52	|	98.13	|	86.25	|	94.05	|	89.69	|	17.06
| RegLog | 90.18 |	98.15	|	98.04	|	67.29	|	52.89	|	73.98	|	3.92
| RegLog_balanced | 96.48	|	98.10	|	97.41	|	86.21	|	96.59	|	87.13	|	4.11
| BERT_50 | 96.40	|	98.32	|	97.54	|	82.93	|	92.12	|	88.95	|	824.75
| BERT_200 | 97.30 |	98.81	|	98.68	|	86.36	|	98.86	|	89.35	|	3229.33
