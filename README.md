# NEU CS7980 Capstone Project Tornado prediction- Team 1

## Project Description - **Tornado Prediction**
-   Background: We are exploring severe weather predictions and would like to explore **tornado** predictions.
-   Goal: Predict tornado probability and intensity maps based on radar activity map, satellite cloud map, and weather maps (temperature, humidity, cloud, pressure, and etc). 

 

-   Research Objectives 
    -   Build machine learning and deep learning models to make predictions
        -   First step: build linear models/logistic models and physics based model (parameterization from literature) as a baseline
        -   Second: build and finetune a LightGBM model (diagnostic model at one location and timestamp)
        -   (Stretch) Third: Make the model aware of spatial context
        -   (Stretch) Fourth: Make the model aware of temporal context
    -   Success metric
        -   Performance improvement against baseline in first step
-   Data Source
    -   Tornado occurrences in the U.S. for past years
    -   U.S. radar reflectivity maps
    -   Weather variable maps
    -   Satellite cloud maps
    -   Topography map
