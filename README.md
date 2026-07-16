Email Spam Classification Application
   -A simple web application built with Streamlit that classifies emails as Spam or Not Spam using a pre-trained Machine Learning model.

#Features
   >Classify emails as spam or not spam in real-time.
   >Easy-to-use web interface powered by Streamlit.
   >Built with Machine Learning for accurate predictions.

#Tech Stack
  Backend: Python
  Frontend: Streamlit
  Machine Learning: Pre-trained model using Scikit-learn
  Data Transformation: CountVectorizer

#Project Structure
.
├── spam123.pkl               # Pre-trained ML model (saved with pickle)
├── vec123.pkl                # CountVectorizer object (for transforming text)
├── spamDetector.py                    # Main Streamlit app code
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
├──SpamDetector.ipynb         # jupyter notebook 

#How to Run
>Clone the repository:
git clone https://github.com/Sociallypriya/AICTE_SpamEmailClassification.git

>Navigate to the project directory:
cd AICTE_SpamEmailClassification_Project

>Install the required dependencies:
pip install -r requirements.txt

>Run the application:
streamlit run spamDetector.py

>Open your browser at http://localhost:8501 to view the app.

#Usage
Enter the email content in the provided text area.
Click the Classify Email button.
The app will display whether the email is spam or not.

#Example
Input:
Congratulations! You've won a $1,000 Gift Card. Click here to claim your prize!
Output:
This is a Spam Email.

#Model Details
Model: Pre-trained classifier (e.g., Naive Bayes, SVM, etc.)
Dataset: Trained on a dataset of labeled emails (e.g., Ham vs Spam emails).

#Dependencies
Python 3.10.5
Streamlit
Scikit-learn
Pickle

#Contribution
Thank U,for all the Contributions!

#License
This project is licensed under the AICTE License.

Author
Priya Kumari
sociallypriya@gmail.com 

