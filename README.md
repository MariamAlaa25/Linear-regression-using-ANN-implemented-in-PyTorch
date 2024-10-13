
Objective
------------------------------------------------------------
The objective of this task is to conduct linear regression with an Artificial Neural Network (ANN) built in PyTorch, focusing on analyzing the relationship between prices and area within a dataset. The goal is to create, train, and assess the ANN model, along with visualizing the results.

Dataset Description
-------------------------------------------------------------
The dataset consists of 13 columns:

price: House price (in currency units)

area: Area of the house (in square feet)

bedrooms: Number of bedrooms

bathrooms: Number of bathrooms

stories: Number of floors (stories)

mainroad: Whether the house is on the main road (yes/no)

guestroom: Availability of a guestroom (yes/no)

basement: Whether the house has a basement (yes/no)

hotwaterheating: Presence of hot water heating (yes/no)

airconditioning: Presence of air conditioning (yes/no)

parking: Number of parking spaces

prefarea: Preferred area status (yes/no)

furnishingstatus: Furnishing status of the house (furnished, semi-furnished, unfurnished)

This dataset describes the relation between the the aspects of a house and its price

Steps to Run the Code in Google Colab
---------------------------------------------------------------

1-Open Google Colab: Navigate to Google Colab.

2-Create a New Notebook: Click on "New Notebook" to create a fresh workspace.

3-Upload the Dataset:

-In the left sidebar, click on the folder icon.

-Click on the upload icon to upload orbit.csv.

4-Install Dependencies (if necessary):
You can install any missing libraries using:

!pip install numpy pandas torch matplotlib scikit-learn

Dependencies
--------------------------------------------------------------
-Python Libraries:

      -numpy

      -pandas

      -torch

      -matplotlib

      -scikit-learn
