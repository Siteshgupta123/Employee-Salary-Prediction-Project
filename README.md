<p align="center">
  <a href="https://edunetfoundation.org/" target="blank">
    <img src="https://edunetfoundation.org/wp-content/uploads/2022/11/Edunet-Foundation-logo.png" alt="Edunet Foundation" height="50">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.ibm.com/" target="blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/IBM_logo.svg" alt="IBM" height="45">
  </a>
</p>


# Employee Salary Prediction App

A Streamlit-powered web app that predicts whether an individual's annual salary is likely to exceed ₹50,000 based on demographic and financial attributes. Built during internship at Edunet Foundation under IBM mentorship.

---

## Features
- Clean and branded UI with Edunet & IBM logos
- Animated result feedback (balloons , snow )
- Human-readable dropdowns for categorical features
- Full input summary with prediction result
- Integrated ML model trained on the Adult dataset
- Deployable via platforms like Render

---

##  Sample Input vs Predicted Output
| Feature             | Sample Value        |
|---------------------|---------------------|
| Age                 | 35                  |
| Workclass           | Private             |
| Education Level     | Bachelors           |
| Marital Status      | Married             |
| Occupation          | Exec-managerial     |
| Relationship        | Husband             |
| Race                | White               |
| Gender              | Male                |
| Capital Gain        | 5000                |
| Capital Loss        | 0                   |
| Hours Per Week      | 45                  |
| Native Country      | India               |

### Predicted Output
>  **Predicted Salary:** More than ₹50,000/year  
>  *Congratulations! You're projected to earn above the threshold!*

---

##  Project Structure
```
Employee-Salary-Prediction-Project/
├── app.py          # Main Streamlit app 
├── employee salary prediction.ipynb  # Model training notebook 
├── best_model.pkl               # Serialized trained ML model 
├── adult.csv                    # Cleaned dataset 
├── requirements.txt             # All dependencies 
├── README.md                    # This file
```


---

##  Installation & Run Guide
### Setup Instructions

1. **Clone the repository**
```
   git clone https://github.com/Siteshgupta123/Employee-Salary-Prediction-Project.git
   cd Employee-Salary-Prediction-Project
```
2. **Create a virtual environment (optional but recommended)**
```
python -m venv venv
venv\Scripts\activate   # On Windows
```
3. **Install dependencies**
```
pip install -r requirements.txt
```
4.**Run the app**
```
streamlit run app.py
```
-------------------
## Deployment
You can deploy this project on **Render**, **Streamlit Community Cloud**, or any hosting platform that supports Python + Streamlit.

-----------
