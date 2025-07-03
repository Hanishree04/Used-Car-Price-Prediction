## Used Car Price Prediction App

This project is a **Streamlit-based web application** that predicts the selling price of a used car based on user input features such as brand, fuel type, engine specs, and more. The machine learning model was trained using a Jupyter Notebook (`CAR.ipynb`) and saved as `model.pkl`.

##  Project Overview

- **Objective**: Predict resale price of used cars using regression
- **Model Type**: Supervised Learning (Regression)
- **Frontend**: Streamlit Web App (`main.py`)
- **Model Training**: Jupyter Notebook (`CAR.ipynb`)
- **Deployment**: Local using Streamlit

---

##  Features Used

| Feature             | Description                      | Example Values            |
|---------------------|----------------------------------|---------------------------|
| Car Brand           | Manufacturer                     | Maruti, Hyundai           |
| Year                | Year of manufacturing            | 1994 – 2024               |
| KMs Driven          | Total kilometers driven          | 11 – 200000               |
| Fuel Type           | Type of fuel                     | Petrol, Diesel            |
| Seller Type         | Type of seller                   | Dealer, Individual        |
| Transmission Type   | Manual or Automatic              | Manual, Automatic         |
| Owner Type          | Number of previous owners        | First Owner, Second Owner |
| Mileage (kmpl)      | Fuel efficiency                  | 10 – 40                   |
| Engine (CC)         | Engine capacity                  | 700 – 5000                |
| Max Power (bhp)     | Maximum power                    | 0 – 200                   |
| Seats               | Seating capacity                 | 5 – 10                    |

---

Run the app using:
```bash
streamlit run main.py
---

It will open in your browser at: http://localhost:8501
---

## Project Structure
bash
Copy
Edit
├── main.py          # Streamlit frontend
├── CAR.ipynb        # Jupyter notebook for model training
├── model.pkl        # Trained ML model
├── README.md        # Documentation

