# Reports

## Confusion Matrix

Confusion Matrix para o problema descrito

 | \\/ true - predicted > | atypical | indeterminate | typical |
| ----------------------- | -------- | ------------- | ------- |
| **atypical** | 7 | 10 | 76 |
| **indeterminate** | 4 | 47 | 156 |
| **typical** | 2 | 34 | 510 |

## You must know

**Precision**: What proportion of positive identifications was actually correct? \
When it predicts a `Class` is true, it is correct `Precision` of the time.

**Recall**: What proportion of actual positives was identified correctly? \
Correctly identifies `Recall` of all true `Class`. 

**F1-SCORE**: Combines the **Precision** and **Recall** of a classifier into a single metric by taking their harmonic mean \

## Classification Report

|               | precision | recall | f1-score | support |
| ------------- | -------- | ------------- | ------- | ------- |
| **atypical**      | 0.54 | 0.08 | 0.13 | 93 |
| **indeterminate** | 0.52 | 0.23 | 0.32 | 207 |
| **typical**       | 0.69 | 0.93 | 0.79 | 546 |
|                   |  |  |  |  |
|  **accuracy**     |      |      | 0.67 | 846 |
|  **macro avg**    | 0.58 | 0.41 | 0.41 | 846 |
|  **weighted avg** | 0.63 | 0.67 | 0.60 | 846 |
