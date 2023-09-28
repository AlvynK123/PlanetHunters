# PlanetHunters

### Project Information
- Using Machine Learning/Visualizing Light Curves with given data to determine which model is best suited to find out the existence of exoplanets. Datasets were gathered from NASA's Exoplanet Archive. Wrote queries following the structure compatiable with the Exoplanet Archive's API
- Handled and tested different graphs and models through Machine Learning in Google Colaboratory
- Extracted data sets from the NASA Exoplanet Archive to manipulate data with Pandas in Python
- Implemented Synthetic Minority Over-sampling Technique to augment found data as a means to develop a Logisitc Regression Model: Tested distinct classification models to yield the best result of 99.97% accuracy

### Results
KNN Algorithm
- Relies on Clustering to Separate exoplanet and non-exoplanet data
- Accuracy: ~99.31% (train) , ~99.12% (test)

Logisitc Regression
- Assigns each datapoint a probability of being an exoplanet. Decides based on this probability whether or not datapoint is an exoplanet.
- Accuracy: ~99.97% (train) , ~99.56% (test)
- SMOTE (Synthetic Minority Oversampling Technique) to augment our data: Using existing minority data (exoplanets), SMOTE creates more minority data to help balance the dataset. This ensures that the model will not have a bias towards the majority data.

<img width="545" alt="Screenshot 2023-09-28 at 12 39 14 AM" src="https://github.com/AlvynK123/PlanetHunters/assets/35633980/52614996-0847-4ca3-8374-80fa7c0d3791">


Complex Machine Learning Algorithms
- MLP (Multi-layer Perceptron) with augmented data [Provided an accuracy of 99.83%]
- Neural Networks (Tensorflow and Keras) [Yielded an accuracy 99.47%]
- CNN (convolutional Neural network) [Accuracy yielded is 99.67%]

### Real World Application
NASA’s efforts currently use the transit photometry method as a reliable and logically provable way to measure the consistency of orbits and therefore the presence of an exoplanet. 
The use of the logistic regression model provides the easiest, most robust, and reliable way or method of accessing and conveying information relevant to transit photometry, specifically when considering factors such as ease of use, readability, and relative simplicity to code. 

An additional aspect of data that would greatly help the entire process would be to use transit photometry as a means to gather more data about the exoplanet itself, once the patterns of dips have been determined and the exoplanet been confirmed. Qualities of the exoplanet like mass could be easily expanded upon, whereas more complicated details like orbiting moons, atmospheric data, and type of planet could be collected using a potentially more powerful descendant or enhancement of transit photometry, especially when considering the possibilities that could be collected using present methods. 
