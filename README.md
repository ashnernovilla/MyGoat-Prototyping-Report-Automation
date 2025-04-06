# 🐐 Robotic Mowing Machine Prototyping Report Automation

## Overview  
This project automates the generation of prototyping reports for **Robotic Mowing Machine**, streamlining the process of collecting, analyzing, and presenting prototyping data. By integrating SQL-based data extraction, LLM-powered narrative generation, and automation pipelines, the system ensures timely, consistent, and accurate reports with minimal manual effort.

## 👤 Contributor  
**Ashner Gerald Novilla**  
Software Engineer 
Expert in Big Data, Data Science, and Automation

## 📌 Features

- 🔄 **SQL Integration**: Dynamically fetches data (e.g., test metrics, logs, versioning) from internal databases  
- 🤖 **LLM-Powered Narratives**: Automatically generates summaries and explanations for data insights  
- ⚙️ **Automation Pipelines**: Fully automates data handling, formatting, and report creation  
- 📊 **Excel GUI Support**: Provides a user-friendly input method for non-technical users via Excel forms  

## 🧰 Tech Stack

- **Language**: Python  
- **Environment**: Jupyter Notebook  
- **Libraries**: Pandas, IPython, OpenAI/LangChain (for LLMs), pyodbc/sqlalchemy (for SQL)  
- **Interface**: Excel-based GUI input, Notebook-based output

## 🛠 How It Works

1. **User Inputs**  
   - Provided via Excel or directly in the notebook (e.g., prototype ID, date range)

2. **Data Extraction**  
   - SQL queries pull relevant metrics from internal databases

3. **Data Processing & Summarization**  
   - Pandas handles computation; LLM generates contextual narratives

4. **Report Generation**  
   - A formatted report is produced in Markdown or HTML within the Jupyter Notebook

## ⚠️ Expected Challenges

- Handling edge cases in input formats or incomplete data  
- Maintaining LLM prompt consistency for varied reporting structures  
- Ensuring compatibility across different database systems or Excel versions  

## 📂 Folder Structure  
```
MyGoat_Report_Automation/
│
├── data/                 # Sample input files or templates
├── notebook/             # Main Jupyter Notebook for automation
├── output/               # Generated reports
├── assets/               # Images, logos, visuals (if needed)
├── README.md             # Project documentation
└── requirements.txt      # Dependencies
```

## ✅ Goals & Outcomes

By the end of the project:
- Reduce manual reporting time by 50%+
- Increase reporting accuracy and consistency
- Provide a repeatable, scalable solution for ongoing prototyping cycles

## 📌 Future Enhancements

- Web-based UI for broader accessibility  
- Full CI/CD integration for continuous delivery of reports  
- Dashboard integration for real-time data visualization  
