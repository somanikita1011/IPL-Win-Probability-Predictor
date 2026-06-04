🏏 IPL Win Probability Predictor
A real-time Machine Learning web application that predicts the winning probability of IPL teams during a match chase — just like live broadcast overlays!
Built as part of the InternPE Internship Program.

🎯 What It Does
Given the current match situation, the app instantly predicts:

🟢 Win Probability of the batting team
🔴 Loss Probability of the batting team


🖥️ Demo

Enter match details → Get instant win/loss probability!

InputExampleBatting TeamMumbai IndiansBowling TeamChennai Super KingsHost CityMumbaiTarget Score180Current Score90Overs Completed10Wickets Lost3

⚙️ Tech Stack
ToolPurposePythonCore ProgrammingPandas & NumPyData ProcessingScikit-learnML Model & PipelineStreamlitWeb App UIPickleModel Serialization

📊 Features

✅ Trained on real IPL ball-by-ball data (Kaggle)
✅ Feature Engineering — CRR, RRR, Balls Left, Wickets Left
✅ ML Pipeline with OneHotEncoding + Logistic Regression
✅ Interactive Streamlit Web App
✅ Predicts probability in real-time


🚀 How to Run Locally
1. Clone the repository
bashgit clone https://github.com/somanikita1011/IPL-Win-Probability-Predictor.git
cd IPL-Win-Probability-Predictor
2. Install dependencies
bashpip install -r requirements.txt
3. Run the app
bashstreamlit run app.py
4. Open in browser
http://localhost:8501

📁 Project Structure
IPL-Win-Probability-Predictor/
│
├── app.py                          # Streamlit web app
├── pipe.pkl                        # Trained ML model
├── matches.csv                     # IPL matches dataset
├── deliveries.csv                  # Ball-by-ball dataset
├── Make_a_IPL_WINNING_TEAM_PREDICTION.ipynb  # Jupyter Notebook
├── requirements.txt                # Dependencies
└── README.md                       # Project documentation

🧠 ML Model Details

Algorithm: Logistic Regression
Pipeline: ColumnTransformer + OneHotEncoder + Logistic Regression
Input Features:

Batting Team, Bowling Team, City
Runs Left, Balls Left, Wickets Left
Current Run Rate (CRR)
Required Run Rate (RRR)
Target Score


Output: Win/Loss Probability (%)


📦 Dataset

Source: Kaggle IPL Dataset
Files used: matches.csv and deliveries.csv


🙏 Acknowledgements

InternPE for providing this internship opportunity
Kaggle for the IPL dataset
Streamlit for the amazing web framework


👩‍💻 Author
Nikita
B.Tech CSE (AI & ML) — CMR Technical Campus
