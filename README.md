# Knime-Workflows
Cheminformatics Workflows for Knime

## FW_Enumerator
- FW is Free-Wilson, a method for predicting activities based on R-Groups
- The workflow enumerates all possible combinations of R-Groups and predicts properties if the data is available

## Pairwise Draw
- The chemist draws a change from one structure to another and the workflow finds all pairs with that exact change
- The workflow then shows the effects of that change on selected properties and provides statistics on the effect

## Spotfire Data Creator
- The workflow cleans the data, adds Series annotations, adds binned columns, creates new columns derived from the existing columns, and does R-Group deconvolution
- The result is an SD File and a CSV file that can then be imported into Spotfire for data analysis
