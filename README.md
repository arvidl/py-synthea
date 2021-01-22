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
Make a new kernel:
```
python -m ipykernel install --user --name synthea-fhir --display-name "SYNTHEA-FHIR"
```

### Run

```
conda activate synthea-fhir 
jupyter notebook
```


### License (for some notebooks)
Copyright 2020 The MITRE Corporation

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
