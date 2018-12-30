# Genetics Homework

We have a set of patients for which we've done a bunch of DNA variants analyzes.

One analysis is called sample. It is represented by table. Table's row represents one patient's variant. Sample contains variants of multiple patients.

We need to merge analyzes' data and load them to the database. Then we will do a bunch of specific selections which will be exported to the CSV files.


### Input Files

**input/patients.csv** - table of patients  
**input/variants/*** - tables of patients' variants


### Task 1) Merge the variants into the single file

- Sample name is represented by file's name (sample_name.csv)
- Preserve the sample name as a new column in merged table


### Task 2) Import data to the database

- Create a new database (use your favourite engine - e.g. SQLite)
- Create table patients
- Create table variants
- Import the data


### Task 3) Create following selections

- Select variant counts for every patient
- Select variant counts for every sample
- Select variant counts for every chromosome
- Select counts or insertions, deletions and substitutions for every patient (export to the .csv file)
- Select counts or insertions, deletions and substitutions for every male patient younger than 40 (export to the .csv file)