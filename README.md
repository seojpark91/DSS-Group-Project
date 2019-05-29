# Fast Campus Data Science School Classification Group Project   
## Quora Insincere Questions Text Classification   
   
### Objective : Detect toxic content to improve Quora online conversations   

### Model:  
- CountVectorizer : ngram_range = (1,2)   
- Logistic Regression: class_weight = {0: 0.1505, 1 : 0.8494}    

### Evaluation : F1 Score  
- F1=2⋅precision⋅recall/(precision+recall)  

### Final Score: 
| &nbsp;| precision | recall | f1 score |
|-|-|-|-|
| 0 | 0.97 |  0.98 | 0.97 |
| 1 | 0.71 | 0.58 | 0.64 |
