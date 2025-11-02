# Verdure--Intelligent-Crop-Planner-Application-with-MATLAB
This repository contains the source code for a smart farming decision support tool, built entirely in MATLAB and App Designer. The project was developed as a team submission for the National MATLAB Competition held in Nigeria  

The application leverages a Random Forest machine learning algorithm to analyze environmental and agricultural data. Based on user inputs, it provides a comprehensive, personalized farming plan.

Key Features
Personalized Inputs: Allows users to input specific parameters like Location, Soil Type, Crop, Soil pH, and Water Retention.

Intelligent Planning: Automatically generates an optimal Planting Schedule and a visual Crop Planning Calendar (Month-by-Month).

Yield Potential Analysis: Displays a bar chart comparing the predicted yield potential of various crops for the selected region.

Actionable Recommendations: Provides a clear list of actions (e.g., "Improve Soil Moisture," "Consider Irrigation") to help farmers increase yield.

Climate Visualization: Integrates a Temperature Map to visualize the climate data for the selected location.

Core Technology
The predictive engine of this application is a Random Forest (RF) algorithm. The RF model is trained on climate, soil, and crop datasets to find optimal conditions and predict outcomes, which are then translated into the easy-to-understand recommendations and schedules you see in the app.

How to Run
Open the .mlapp file in MATLAB.

Click Run from the App Designer toolstrip.

In the running app:

Upload your climate dataset using the "Import File" button.

Select your parameters from the "Input Details" panel.

Click "View Personalized Plan" to generate the results.
