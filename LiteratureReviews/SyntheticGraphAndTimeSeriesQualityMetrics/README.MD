## Synthetic Graph and Time Series Quality Metrics

To identify robust and field-accepted quality metrics for evaluating synthetic **graph** and **time-series** data, we conducted three targeted literature reviews. Each review was designed to surface studies that (i) generate synthetic data in the respective modality and (ii) report evaluation approaches that can be consolidated into a systematic metric inventory. Detailed query configurations, as well as the associated selection and filtering criteria, are documented in the accompanying Excel file.

### Literature Search Queries

#### Graph Data Generation
```text
("Synthetic Data" OR "Artificial Data") AND ("Generat*" OR "Synthesis") AND ("Graph" OR "Network Data")
```
[LitRev_SyntheticGraphDataGeneration.xlsx](./LitRev_SyntheticGraphDataGeneration.xlsx)

#### Temporal Data Generation
```text
("Synthetic Data" OR "Artificial Data") AND ("Generat*" OR "Synthesis") AND ("Temporal" OR "Time Series")
```
[LitRev_SyntheticTemporalGraphDataGeneration.xlsx](./LitRev_SyntheticTemporalGraphDataGeneration.xlsx)

#### Temporal Graph Data Generation
```text
(("Synthetic Data" OR "Artificial Data") AND ("Graph" OR "Network Data") AND ("Temporal" OR "Time Series"))
OR
(("Synthetic Data" OR "Artificial Data") AND ("Dynamic Graph" OR "Temporal Network"))
```
[LitRev_SyntheticTemporalGraphDataGeneration.xlsx](./LitRev_SyntheticTemporalGraphDataGeneration.xlsx)

### Selection and Extraction Procedure

After identifying candidate papers on synthetic data generation, we applied a two-stage screening process:

1. Comparative-study filter: We retained only studies that compare two or more generative approaches, ensuring that evaluation metrics are used in a comparative setting rather than as isolated diagnostics.
2. Metric extraction and framework mapping: From the retained set, we extracted all evaluation metrics and mapped them to the dimensions of our Synthetic Data Quality Framework, enabling a structured synthesis across modalities and study designs.

The resulting metric inventory and its categorization are provided in: [Evaluation_SyntheticDataMetrics.xlsx](./Evaluation_SyntheticDataMetrics.xlsx)