## Repository Structure

- `Converted_binned_sequencing_data/`  
  Contains preprocessed histone modification data, binned around the transcription start sites of genes

- `GE_Labels/`  
  Contains gene expression (GE) labels per cell line, derived from RNA-seq data. Each gene is labeled as either high or low expression

- `Gene_Splits/`  
  Stores training, validation and test gene splits per cell line to ensure fair and reproducible evaluation

- `PatternChrome_Results/`  
  Default output directory for PatternChrome runs, including extracted patterns, feature matrices, log files and result summaries

- `PatternChrome_Results_SmartBalanced/`  
  Contains the results of the tuned model after hyperparameter optimization
