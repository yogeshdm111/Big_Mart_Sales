#BigMart Sales Dataset - Predict the sales of a store using ML algorithms

#Goal-
This Flask web application predicts item outlet sales based on various input parameters such as item weight, visibility, MRP, outlet details, etc. The predictive model is trained using machine learning techniques and deployed using Flask.

#Table of Contents

  Overview
  Features
  File Structure
  Usage
  Technologies Used
 
  
  #Overview
  
    This project uses a Random Forest Regression model (out of many regressor models) to predict sales based on various input features such as item weight, visibility, 
    MRP, and store details like establishment year, size, location, and type.

  #Features

    Predict sales for new store items based on user inputs.
    Visualize data distributions and relationships using seaborn and matplotlib.
    Implement Flask web framework for user interaction and model prediction.
    Save and load trained machine learning models using pickle.

  #File Structure
  
    main.py: Flask application with routes for rendering HTML templates and handling model predictions.
    src/: Directory containing the machine learning model (rf_model.pkl),ipynb file and datasets.
    static/: Directory containing static files like CSS and images for the HTML templates.
    templates/: Directory containing HTML templates (home.html).

  #Usage

    Open VS code-Open project folder-Open src folder-open ipynb file and run it
    Open main.py file-open terminal-install requiremnts.txt to install all dependencies-run main.py-click on generated url in terminal
    Navigate to http://localhost:5000/ in your web browser.
    Fill in the required details such as item weight, fat content, visibility, etc.
    Click on the "Predict" button to see the predicted sales for the item

  #Technologies Used
  
    Python
    Flask
    Pandas
    NumPy
    Scikit-learn
    Seaborn
    Matplotlib
    HTML/CSS

    

