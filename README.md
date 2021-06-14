# Airbnb-EDA-and-Regression
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://user-images.githubusercontent.com/39674365/121967230-4c981a80-cd70-11eb-85a3-6d8e5a9e8e95.png" alt="Logo" width="220" height="80">
  </a>

  <h3 align="center">Airbnb-EDA-and-Regression</h3>

  <p align="center">
    <br />
    <a href="https://colab.research.google.com/drive/1aWuot455_nNXtPis9huD1psBGbdUm2b0?usp=sharing">Demo</a>
    ·
    <a href="./Document.pdf">Report</a>
    ·
    <a href="./Notebook.ipynb">Notebook</a>
      ·
    <a href="https://drive.google.com/file/d/11eF32svdn-NPLaKpItYsbBp5T45stJMP/view?usp=sharing">Video</a>

  </p>
</p>
Big data exploration and analysis on Airbnb dataset as well as regression model for price prediction of entities
Airbnb Price Prediction Challenge

## Problem definition

Airbnb, Inc. operates an online marketplace for lodging,primarily homestays for vacation rentals,
and tourism activities. It is based in San Francisco,California.
Our problem is going to be analysis and explorationon the given dataset we provided in the
proposal and modeling the data in order to predictthe price of an instance.

## Data overview

The dataset consists of 74,111 entries, splitted intothe following groups of data types.


## Model selection and tuning and Results

```
The best outcome came for the XGBoost regressor , andgot a very good MSE with respect to
the published ones on the competition and near tosome of them and higher than some others
which is good as well as we have tried RandomForestRegressor and tuning done on ithad
very similar results but was a bit less than it aswell as trying Linear Regression but it was
less than them.
```
```
Training MSE: 0.2005
Validation MSE: 0.201
```
```
Training r2: 0.6092
Validation r2: 0.6139
```
## Future work

- Use reviews dataset on each property and making sentimentanalysis on them in order to add
    new feature to each property
- Using more larger dataset consists of multiple placesand countries




<!-- CONTACT -->
## Contact

Mohamed Mokhtar - rrrokhtar@gmail.com

