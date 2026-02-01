# Loan_Approval_Prediction_System
A machine learning project that predicts loan approval decisions based on applicant financial and demographic data using  LogisticRegression, KNeighborsClassifier, GaussianNB

📊 Dataset
The dataset contains 1,000 loan applications with 20 features: <br>
<b>Applicant Information:</b>

- Demographic: Age, Gender, Marital Status, Education Level, Dependents
- Employment: Employment Status, Employer Category, Applicant Income, Coapplicant Income
- Financial: Credit Score, Existing Loans, DTI Ratio, Savings, Collateral Value


🛠️ Technologies Used
Programming Language: Python 3.x <br>
<b>Libraries: </b>

- Data Processing: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn

🤖 Models Implemented

    Logistic Regression
    K-Nearest Neighbors
    Gaussian Naive Bayes
<b>Preprocessing: </b>

    StandardScaler
    LabelEncoder
    OneHotEncoder
    SimpleImputer
<b>Evaluation: </b>

    train_test_split
    accuracy_score
    precision_score
    recall_score
    f1_score



📈 Results
<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>F1-Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Logistic Regression</td>
      <td>88%</td>
      <td>81%</td>
      <td>78%</td>
      <td>80%</td>
    </tr>
    <tr>
      <td>K-Nearest Neighbors</td>
      <td>75%</td>
      <td>64%</td>
      <td>52%</td>
      <td>57%</td>
    </tr>
    <tr>
      <td>Naive Bayes</td>
      <td>87%</td>
      <td>84%</td>
      <td>70%</td>
      <td>76%</td>
    </tr>
  </tbody>
</table>
