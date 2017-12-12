# Norwegian datasets published in GBIF
About the archive for Norwegian datasets published in GBIF

Data archiving in GitHub & Zenodo require each dataset to be in a separate repositry
https://guides.github.com/activities/citable-code/



# Archive dataset with GitHub and Zenodo

## GitHub
* Create a new repository for the new dataset to publish in GBIF.no
* Configure write permissions for team "GBIF.no" in Settings-Collaborators & teams
* Add the original source datafile provided by the data owner.
* Add the Darwin Core archive file created by IPT.
* Create a simple README.md for the repository with the dataset.
* Remember to include a text file LICENSE.txt (in GitHub).

## Zenodo
* Login to Zenodo and configure webhooks on repositories (once).
* Select your user profile, GitHub, and settings: https://zenodo.org/account/settings/github/
* Toggle the flip from "off" to "on" for the GitHub repository of the dataset to archive.

## Return to GitHub 
* Select dataset-repository and make a release (select menu item releases).
* Release-tag: v1.1
* Release-title: [organization_short_dataset_name_version]
---
* Add a DOI button to the GitHub README.md
* [![DOI](https://zenodo.org/badge/DOI/add-zenodo-doi.svg)](https://doi.org/add-zenodo-doi)
* [![DOI](https://zenodo.org/badge/DOI/add-gbif-doi.svg)](https://doi.org/add-gbif-doi)

## GBIF.no IPT
* Add the Zenodo DOI under metadata -- External links
* Name: Zenodo data archive
* Download URL: https://doi.org/10.5281/zenodo....
* Data format: Darwin Core archive
