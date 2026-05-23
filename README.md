Machine Learning Based Meteorite Classification Using Geochemical Features

This project aims at using machine learning to classify metoerites into one of 6 classes (H, L, LL, Carbonaceous, Entatite and Achondrite), based on the inputs of feature values that a user gives. The user can choose the features
the want to give as an input and then just enter the values of those features within the valid range.

The dataset for this project has been obtained from astromat where it was synthesised using the filters in 'Search Astromat Synthesis'. The dataset has got 245 samples spanning all the six classes, 
and 35 fundamental geochemical features, spanning oxides, rare earth elements, noble gases, and a few other elements. The features with a high numner of holes (missing values) in them were eliminated entirely, while the holes for 
other features were filled using class-wise mean imputation, ultimately giving rise to 35 fundamental geochemical features. 29 more derived features were added, which include ratios, averages, etc. So the dataset 
that ended up being used by the model had 245 samples and 64 features in total.

The model used was a Random Forest model. The reason for choosing this model in particular was 

