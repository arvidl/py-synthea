# py-synthea
Synthea Patient Generator and FHIR: Fast Healthcare Interoperability Resources in Python

## Synthea Patient Generator

## FHIR: Fast Healthcare Interoperability Resources. Web standard for health interop

## CDS Hooks: Clinical Decision Support Hooks. Web standard for CDS in the EHR workflow

- https://github.com/synthetichealth/synthea
- https://github.com/smart-on-fhir/client-py
- http://docs.smarthealthit.org/client-py/
- http://docs.smarthealthit.org/
- https://github.com/AlgorexHealth/bmi-fhir/blob/master/FHIR%20BMI%20Results.ipynb
- https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-019-0793-0
- https://www.mitre.org/publications/project-stories/for-patient-data-synthea-is-the-missing-piece-in-health-it


### INSTALL

```
conda create -n synthea-fhir python=3.8
conda activate synthea-fhir 
conda install git
conda install pip
conda install jupyter 
conda install ipykernel
conda install pandas
conda install pandas
conda install seaborn
conda install -c conda-forge altair vega_datasets

pip install fhirclient 
```

### Run

```
conda activate synthea-fhir 
jupyter notebook
```

```
python -m ipykernel install --user --name synthea-fhir --display-name "SYNTHEA-FHIR"
```
