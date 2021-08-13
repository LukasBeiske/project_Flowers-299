# project_Flowers-299
Project work for the 2021 "Maschinelles Lernen für Physiker*innen" seminar at TU Dortmund by [Lucas Cremer](mailto:lucas.cremer@udo.edu),
[Daniel Wall](mailto:daniel.wall@udo.edu) and [Lukas Beiske](mailto:lukas.beiske@udo.edu).

## Dataset
_Flowers-299_ by Bogdan Cretu hosted on [kaggle](https://www.kaggle.com/bogdancretu/flower299) with the _CC0: Public Domain_ License.
Please download the dataset and save it into a folder named `Flowers299` in the same parent directory as the repo, if you want to run the code in this repo.

## Google Colab
Training of the networks is mostly done by uploading notebooks to _Google Colaboratory_ for faster computing resources.
The first three cells in the `hyperparameter_tuning.ipynb` notebook can only be executed in Colab and a slight change in cell 5 has to be made, if you want to run this notebook locally:
Change `path = drive_path` to `path = local_path`.
