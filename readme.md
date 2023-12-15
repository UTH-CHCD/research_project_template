# Project Name

Last Update: YYYYMMDD

This is a readme file for a template project for a CHCD research project. Alter it to fit your project. AKA, don't leave a folder called `subproject01` called `subproject01`. Write a brief description of the project here. 

## Personnel

Please list the personnel/responsibilities here.

# Folder Structure
This is the default folder structure of the template. Edit it as you see fit update the directory tree below to reflect that. 

Try to avoid people's names as subdirectories, as that can lead to later confusion. Keep data and code separate! Keep raw data and processed data separate! 

```
|-- data/
|   |-- raw
|   |-- ancillary
|   |-- metadata
|   |-- processed
|-- output/
|   |-- reports
|   |-- tables
|-- scripts/
|   |-- analysis/
|   |   |-- subproject01
|   |   |-- subproject02
|   |-- pipeline
|   |-- ad-hoc
|-- documentation/
|   |-- dictionaries
|   |-- logic
|-- readme.md
|-- log.txt
```

Now, you will describe anything important about the folders. 

## Data Folder

This is a template setup, so the needs of your project may differ, but please give any explanation needed if you need to clarify something. 

* The `raw` folder contains all raw, unprocessed research data. This could be tables pulled directly from various sources. Any changes or outputs using raw data are saved in the `processed` folder.

* The `ancillary` folder contains crosswalks and stuff like that.

* The `processed` folder contains data files that have been altered (or wrangled) as part of the research process. 

* The `metadata` folder contains any data that was created as part of the research process or that describes relationships between data in the other two Data sub-folders. 

## Documentation Folder

...

## Scripts Folder

...

## Output Folder

...

# Database Info

If you have important tables in the database that could use explaining, explain them here... 

# How to Run

Provide general information on how the project runs, if certain steps get repeated, if something needs to be run first, etc. For example:
```
1. Org X sends a quarterly refresh of data, which we upload to the SQL server using the files in file `pipeline_this_...` which exports the report to `this folder`

2. After refreshing, generate the report in `file_report_maker` and output with the new version to `this_folder`

And so on. 
```

# Prerequisites / Installation

If there are any packages or environments people need installed to run the files, please list them here.

# Other Information

Other information/headers might include:

## Cleaning Steps

## Change Log

## Naming Conventions

Write any naming conventions here. Are reports going to be named a certain way? Write that down. 

