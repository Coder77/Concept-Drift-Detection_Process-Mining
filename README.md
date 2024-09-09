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
