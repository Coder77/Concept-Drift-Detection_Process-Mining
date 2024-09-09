# Concept-Drift-Detection_Process-Mining
1. Data Preprocessing:  
  a. Event logs are initially collected and processed.  
  b. Using the Pm4py [5] module, time series graphs are generated from the
     event logs.
  
2.Concept Drift Detection:
  a. The PELT[6] algorithm is employed to detect concept drift in the time
     series data.  
  b. Concept drift points are identified, indicating significant changes in the
     underlying data distribution.  
3. Cause-Effect Analysis:
Cause-effect analysis is conducted to understand the reasons behind
concept drift occurrences.
a.
Multilayer Perceptron (MLP) [7] models are utilized for cause-effect
analysis.
b.
4. MLP Model Architecture:
a.Two MLP models are implemented:
i.Model 1: Takes only the primary perspective (x) as input.
Model 2: Takes both primary (x) and secondary (y) perspectives as
input.
ii.
The models output loss values representing test_error and
validate_error for evaluation.
