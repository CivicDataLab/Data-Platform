
## Our Goal

We are developing a data platform for users to upload their open data. The application should allow the upload and download of csv data files

## Requirement

Example: [https://data.opencity.in/dataset/bbmp-election-2015](https://data.opencity.in/dataset/bbmp-election-2015)

Data Structure:

1. Every dataset has name, description, tags and multiple csv files(let&#39;s call the csv files as resources)
2. Every resource should have name and one csv file data

Requirement breakdown:

1. API to create and upload dataset along with resource file and other metadata like name, description, tags etc
2. CSV files should be saved in file system
3. Develop db model to store dataset and resource metadata
4. API to list datasets
5. API to display a particular dataset
6. Extra requirements :
  - Create a db model to save uploaded csv data and create a relationship with dataset model
  - Create an API to fetch resource data from db for a given dataset

## Available Data

Resources for dataset 1:

1. [https://justicehub.in/dataset/a1d29ace-784b-4479-af09-11aea7be1bf5/resource/55cfa0a9-58dd-46af-b644-fa68fe3f45cd/download/scheme-category-grants-in-aid-ut-police.csv](https://justicehub.in/dataset/a1d29ace-784b-4479-af09-11aea7be1bf5/resource/55cfa0a9-58dd-46af-b644-fa68fe3f45cd/download/scheme-category-grants-in-aid-ut-police.csv)
2. [https://justicehub.in/dataset/a1d29ace-784b-4479-af09-11aea7be1bf5/resource/0e5974a1-d66d-40f8-85a4-750adc470f26/download/metadata.csv](https://justicehub.in/dataset/a1d29ace-784b-4479-af09-11aea7be1bf5/resource/0e5974a1-d66d-40f8-85a4-750adc470f26/download/metadata.csv)

Resource for dataset 2:

[https://data.opencity.in/dataset/e12e4906-3ac6-4b59-bd95-b5e3c8ae69ac/resource/b8de01b5-5c04-4401-aca4-ba01f2c9e422/download/bbmp-election-results-winner-runnerup-2015.csv](https://data.opencity.in/dataset/e12e4906-3ac6-4b59-bd95-b5e3c8ae69ac/resource/b8de01b5-5c04-4401-aca4-ba01f2c9e422/download/bbmp-election-results-winner-runnerup-2015.csv)

## Recommended Steps

1. Design a schema for dataset and resource in a SQL database
2. Create an API to upload the dataset and resource and save metadata in db and resource file in file system
3. Parse the resource file while upload
4. Create a schema to store the parsed csv file data in db
5. Create APIs to list all datasets/ show a dataset detail given its name/ api to fetch the res data from db using resource id
6. Make the resource file downloadable from the file system.

## What are we looking for

**1. Process:** We want to understand your process. How you identified the challenge, and the solution you arrived upon. So documentation of this process would be a valuable addition.

**2. Skills:** Skill-set with respect to reviewing existing landscape - datasets, identifying insights from the data and being able to convey it in the form of a story.

**3. Communication:** Communication is key in a remote working environment such as ours. We want to observe how you communicate not just through your work but also with us via the various channels we have.

**Timeline**

**1 week.**. Do get back to us with any questions and clarifications.

## How will CDL use the submission?

One of our key values is openness. Our work is under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license and If you choose to, we are happy to exhibit the submission online through our various channels. You are also free to make it part of your portfolio. In case CivicDataLab ends up using any of your work in our live solution(s), we would ensure full disclosure and fair compensation to the creator accordingly.

## Co-creation &amp; Collaboration

At CivicDataLab, we believe in collaboration and co-creation. Feel free to discuss your work with us throughout the given time period either through email or through a scheduled call. We&#39;re more than happy to provide feedback on a continuous basis, and not just at the end of the task. In case you have any questions, don&#39;t hesitate to ping us.

![Shape1](RackMultipart20220801-1-ymt7xr_html_c63ba8322e0ee7b7.gif)
