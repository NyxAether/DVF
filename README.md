# DVF
This git embed the data from https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres-geolocalisees/ and linearize them for use of ML

# Structure
Datasets are separate between differents folder :
 * `original` contains the original data with no modifications
 * `cleaned_data` contains the data modified to be linearized and more convenient to use for machine learning. Some informations are lost due to fusion or commercial selling are suppressed from the dataset

# IPYNB
Each *.ipynb* has different purposes :
 * `restructure_donnees.ipynb` transformed the data from the orignal data to the cleaned_one.
