# README

--

### Title
Pennsylvania Vehicle Crash Investigation  
CMU - 90803 Machine Learning Foundations with Python

### Authors

* Yi Liu
yiliu2@andrew.cmu.edu

* Xinqiao Luo
xinqiaol@andrew.cmu.edu

* Zhexuan Huang
zhexuanh@andrew.cmu.edu



--

### Disclaimer / Sensitive Content

**DISCLAIMER** *The research conducted is based on publicly available data and information and was used solely for academic purposes. It is essential to note that the language used in the datasets or for specific research tasks may contain hateful content due to the nature of the topic car crash. The author recognizes the sensitive nature of the topic of car crash. Any findings or conclusions drawn from the analysis were presented with caution and awareness of the potential impact they may have on affected communities. The author acknowledges the complexity of the issues surrounding this project and recognizes the need for continued efforts to address these problems. This research is intended only to understand the ongoing discourse and address this important issue and contribute to the collective efforts toward creating a more equitable society.*

--

### Project Description
People's travel needs are increasing as society develops, resulting in an increase in
transportation crashes.Traffic accidents can result in financial losses, injuries, and
fatalities. Fortunately, machine learning analysis can provide us with information on
how to avoid crashes, such as adding warning signs, implementing more scientific
speed limits, and improving car safety performance.

Using raw data from various years released by the Pennsylvania Department of
Transportation, we hope to conduct a comprehensive analysis of crash reports and
identify contributing factors, and answering our three initial questions in the below part.


**Key Words** Machine Learning, classification, data analysis, car crash, Pennsylvania vehicle accident

**Questions** 

Question 1: Can we classify the crash severity level of an accident based on factors like whether the driver is young or not, or is distracted or not? If there is a correaltion between some variables, what are the factors that most influence the severity of a crash, and what model should we use?
Classification - target variable: MAX_SEVERITY_LEVEL

Question 2: We have a binary variable that indicates whether serious injuries were involved in the accident. Are the injuries related to the driver's behavior, e.g. drug, alcohol etc.?
Classification - target variable: INJURY_OR_FATAL

Question 3: Can we classify the severity of vehicle damage in accidents based on factors like speed limits, location, and lighting conditions? If so, what environmental factors have the most contribution to the result?
Classification - target variable: DAMAGE_IND

--

### Data Collection

Raw data is obtained from The Pennsylvania Department of Transportation. From the Pennsylvania Crash Information Tool website, 
(https://pennshare.maps.arcgis.com/apps/webappviewer/index.html?id=8fdbf046e36e41649bbfd9d7dd7c7e7e ), we acquire the raw 
datasets of all crash incidents that have happened in Pennsylvania from 2017 to 2021 in each county. The data is divided by years, with 
each year containing a zip file. For each year's data, there are multiple data sheets that contain information about the vehicles, crash information, 
road information, people involved, etc. We merged different datasets and keep useful variables, and created three individual subsets of the data, 
each for one of our questions. Each cleaned sub dataset has different target variables and is uploaded in google drive, named as Q1.csv Q2.csv and Q3.csv.


--

### Running the Project / Getting Started

1. Download raw data from https://drive.google.com/drive/u/1/folders/1tfJqkoUoEjmM4jxa5-fLIVgrI2_OSiI0.
2. Open DataCleaning.ipynb to preprocess the raw data and generated three cleaned dataset Q1.csv, Q2.csv, Q3.csv.
3. For each question we have a correspinding notebook to investigate, refer to Q1_models.ipynb, Q2_models.ipynb, Q3_models.ipynb.
4. Conclusion, results, and future work are stated in each notebook.



