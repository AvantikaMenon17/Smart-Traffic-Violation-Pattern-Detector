Smart Traffic Violation Pattern Detector

Overview  
The Smart Traffic Violation Pattern Detector is a data-driven project designed to analyze traffic violations, identify patterns, calculate risk scores, and predict fines. The system supports better decision-making in traffic management and helps improve road safety.

Objectives  
- Analyze traffic violation data  
- Identify patterns and trends  
- Calculate risk scores  
- Predict fines based on violation severity  
- Provide data visualization for insights  

Features  
- Data cleaning and preprocessing  
- Violation pattern detection  
- Risk score calculation  
- Fine prediction system  
- Interactive visualization using Streamlit  

Technologies Used  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  

Project Structure  
Smart-Traffic-Violation-Detector/  
│── app.py  
│── dataset.csv  
│── requirements.txt  
│── README.md  

How to Run the Project  

1. Clone the repository  
git clone https://github.com/AvanthikaMenon17/Smart-Traffic-Violation-Pattern-Detector.git  

2. Navigate to the project folder  
cd Smart-Traffic-Violation-Detector  

3. Install required libraries  
pip install -r requirements.txt  

4. Run the application  
streamlit run app.py  

Modules  

Data Processing  
- Load dataset using pandas  
- Remove missing and duplicate data  
- Convert date and time formats  
- Create features such as hour, overspeed, and repeat offender  

Risk Score Calculation  
- Assign scores based on violation type  
- Consider speed, frequency of violations, and time  

Fine Prediction  
- Use rule-based logic to calculate fine amount  
- Based on severity and calculated risk score  

Output  
- Visual representation of traffic violation patterns  
- Risk score analysis  
- Predicted fine values  

Conclusion  
This project demonstrates how data processing and machine learning techniques can be applied to real-world traffic data to improve monitoring, analysis, and enforcement systems.
