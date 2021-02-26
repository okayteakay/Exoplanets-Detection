# Exoplanets-Detection
## WHY DETECT EXOPLANETS?
### The habitable zone is the area around a star where it is not too hot and not too cold for liquid water to exist on the surface of surrounding planets. Imagine if Earth was where Mercury is. The Sun would cover entire the sky and  much of Earth’s ocean and atmosphere would boil. "Exoplanets are planets beyond our own solar system." While there are multiple motivations for scientists to search for exoplents, the main one remains the big question - What if some exoplanets have the necessary physical conditions (amount and quality of light from the star, temperature, atmospheric composition) for the existence of complex organic chemistry and perhaps for the development of Life (which may be quite different from Life on Earth)? 
## METHOD OF DETECTION
### Scientists discovered a very efficient way to study these occurrences; planets themselves do not emit light, but the stars around which they orbit do. Considering this fact into account scientists at NASA developed a method which they called Transit method in which a digital-camera-like technology is used to detect and measure tiny dips in a star’s brightness as a planet crosses in front of the star. With observations of transiting planets, astronomers can calculate the ratio of a planet’s radius to that of its star — essentially the size of the planet’s shadow — and with that ratio, they can calculate the planet’s size. Kepler Space Telescope’s primary method of searching for planets was the “Transit” method. 
## Features of Data
### Dataset downloaded from Kaggle. The training dataset consists of about 5087 rows as compared to 570 rows in the test dataset. Number of features/columns = 3197, with each feature being a flux value. 
## Features of the Model
### Initially, we run a code to reduce the amount of memory used by both test and train data frames.
### We use the SMOTE Oversampling method to overcome the challenege of extreme class inbalance.
### Principal Component Analysis to extract relevant features from a set of 3197 features. Through this we choose 23 features out of 3197 features. Combined together, these 23 features capture about 90% of the variance. 
### Prediction Results/Accuracy on Test Set: SVM - 84%, Logistic Regression - 62%, Random Forest - 97%, KNN-65%
