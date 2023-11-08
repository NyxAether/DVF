# DVF
This git embed the data from https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres-geolocalisees/ and restructure them for use of ML

## Data
Since data are only kept 5 years by data.gouv.fr, older data may come from [@jdmichaud](https://github.com/jdmichaud)'s [repository](https://github.com/jdmichaud/dvf) and converted using script transformation provided on [@jdesboeufs](https://github.com/jdesboeufs)'s [repository](https://github.com/etalab/dvf)

## Data Structure
Datasets are separate between differents folder :
 * `original` contains the original data with no modifications
 * `cleaned_data` contains the data modified to be linearized and more convenient to use for machine learning. Some informations are lost due to fusion or commercial selling are suppressed from the dataset

## IPYNB
Each *.ipynb* has different purposes :
 * `restructure_donnees.ipynb` transformed the data from the orignal data to the cleaned_one.

## Future Change
Some changes will be made in the future. This project initially started with aim to analyse some DVF data, but its main purpose now is to store old data from DVF. With this in mind, following changes will be made in the future :
 * All ipynb will be removed and transfered to a different project
 * `cleaned_data` is incomplete and will be restructured to be more complete.
 * Data is currently stored with pickle and compressed using bz2. This might be changed to parquet in the future. It may increased the total size of the project but reduces loading time.
