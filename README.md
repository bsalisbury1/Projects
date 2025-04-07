# Projects

This folder is for practice projects in data science and machine learning.  Projects are joint between Thomas Robacker and Ben Salisbury.  The list of projects are below and containined in each subdirectory.  Links to data sources will be given but the data itself will not be copied here.

## List of projects

1. ImageClassification -- identifying fruits
2. TimeSeriesForecasting -- weather predictions

## Notes *for* the authors

When outputting environment information after updating Python libraries, use

```bash
conda env export > environment.yml
```

to export a YAML file and 

```bash
conda list -e > requirements.txt
```

to export a text file.  It's not clear at this point which one is more advantageous, so do both to be safe.