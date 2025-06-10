# FUTURE_DS_03
 Analyze student event feedback to uncover satisfaction trends and suggest improvements using survey data.
 
📊 College Event Feedback Analysis

🔍 Project Overview
College events like workshops, tech fests, and cultural programs gather valuable student feedback — but are we using it effectively?

In this project, I performed an end-to-end analysis of student feedback collected from campus events using Natural Language Processing (NLP) and data visualization techniques to uncover satisfaction levels, common issues, and actionable insights.

🎯 Objectives
Analyze student feedback data (ratings and comments)

Perform sentiment analysis on text feedback

Visualize satisfaction patterns and trends

Provide key recommendations for event improvement

🗂️ Dataset
Format: Simulated Google Form export (CSV)

Attributes:

Event Name

Event Type (Workshop, Seminar, Tech Fest, Cultural)

Department

Student Year

Rating (1-5 scale)

Feedback (text comments)

⚙️ Tools & Libraries Used
Python 🐍

Pandas

Matplotlib & Seaborn

TextBlob (Sentiment Analysis)

WordCloud

🛠️ Project Steps
Data Loading and Cleaning
Imported CSV data, checked for missing values, and prepared it for analysis.

Rating Analysis
Visualized overall satisfaction levels and calculated average ratings per event and department.

Sentiment Analysis
Used TextBlob to classify feedback as Positive, Neutral, or Negative based on polarity scores.

WordCloud Generation
Created a word cloud to highlight the most common words in student comments.

Visual Insights

Rating distribution

Sentiment distribution

Satisfaction by event type

Average ratings by department

💡 Key Findings
Top-Rated Events: AI Workshop and Tech Fest 2025 received the highest satisfaction.

Common Issues: Delays in event start times and poor sound systems were frequently mentioned in negative feedback.

Event Types: Workshops generally had higher satisfaction compared to seminars.

🧠 Recommendations
Improve punctuality and event management.

Ensure better audio-visual arrangements.

Collect department-specific feedback for future personalization.

📂 Project Structure
text
Copy
Edit
college_event_feedback_analysis/
│
├── college_event_feedback_analysis.ipynb  # Jupyter Notebook with full analysis
├── college_event_feedback.csv              # Simulated feedback dataset
└── README.md                               # Project documentation
🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/deepanshu3012/FUTURE_DS_03
Open college_event_feedback_analysis.ipynb in Jupyter Notebook or Google Colab.

Run all the cells to see the full analysis and visualizations.

🙌 Acknowledgements
This project was developed as part of a College Event Feedback Analysis Internship Task to enhance data analysis and NLP skills.

🔗 Connect with Me
www.linkedin.com/in/deepanshu-joshi-b851102bb
