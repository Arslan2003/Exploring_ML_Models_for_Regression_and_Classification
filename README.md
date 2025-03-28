Detailed Specification

This Coursework is to be completed individually
  
Datasets
Two modified datasets are provided for the two tasks, respectively. The California Housing dataset is for the regression task, and the Titanic dataset is for the classification task. In this regression task, please use the last 190 datapoints (before shuffling) for test. In this classification task, please use the last 140 datapoints (before shuffling) for test.
   To complete this assignment, you must use the data provided on Moodle.
   Submissions based on other data will not be marked and will receive 0 marks.

Report
This coursework is to implement a selection of appropriate machine Learning methods for the two tasks (Regression and Classification). For each task, at least Three machine learning models (one main model and at least two baseline models) are implemented. The main model is the model that you think would be most suitable for the task. You need to clarify the reason for choosing the model and describe it in detail. The baseline models are the models to be compared with the main model. The implemented models MUST contain one or more models that you have learned in the module COMP1816. You need to evaluate these models and analyse the reason why the main model is better/worse than the baseline models. This must be presented in the form of a report to your line manager. This report must be split into the FOUR parts below (shown with the corresponding mark weighting), with marks also being rewarded for the presentation and language in your report. Your report should contain images, tables, and equations to help you demonstrate your work in Parts 2 and 3. It is down to your discretion offences. how many images/tables you wish to include, what they should show and how to split them across the different parts.
Part 1 – Introduction (5 Marks)
This should be a brief summary of what the report contains – the problem you are solving, the algorithms you have implemented, results you have obtained and your conclusions. This should only be between 100-200 words. Marks will be deducted if words more than 300.
Part 2 – Regression (40 Marks)
You are required to import the data and implement at least three regression models to predict housing prices.
You must describe all relevant details of the implementation and clarify the reason for choosing the model and evaluation metrics.
Part 2-1: Pre-processing (10 Marks)
You are required to give a brief introduction to the dataset and describe the detailed procedure that how you pre-processed the dataset (e.g., splitting features and target, drop features, the reason should be clearly stated). 
Part 2-2: Methodology (10 Marks)
You are required to clarify the reason for choosing the regression model as the main model. Also, you need to describe the model in detail (e.g., by using mathematical equations). 
Part 2-3: Experiment (20 Marks)
Part 2-3-1: Experimental Settings You are required to describe the experimental settings in detail, e.g., baseline models, and hyperparameters tuning of all the models. 
Part 2-3-2: Results You are required to select at least one regression evaluation metric and show comprehensive results. The reason for choosing the metric should be clarified. Note that 0 marks will be given if only results are given but no explanation of experimental settings in the report.
Part 2-3-3: Discussion You are also required to compare the results of different models, and analyse the results (e.g., the reason that the main outperforms baselines).

Part 3 – Classification (40 Marks)
You are required to import the data and implement at least three classification models to predict who will survive (and who will not survive).
You must describe all relevant details of the implementation and clarify the reason for choosing the model and evaluation metrics.
Part 3-1: Pre-processing (10 Marks)
You are required to give a brief introduction to the dataset and describe the detailed procedure that how you pre-processed the dataset (e.g, dealing with missing values). 
Part 3-2: Methodology (10 Marks)
You are required to clarify the reason for choosing the classification model as the main model. Also, you need to describe the model in detail (e.g., by using mathematical equations). 
Part 3-3: Experiment (20 Marks)
Part 3-3-1: Experimental Settings You are required to describe the experimental settings in detail, e.g., baseline models, and hyperparameters tuning of all the models. 
Part 3-3-2: Results You are required to select at least one classification evaluation metric and show comprehensive results. The reason for choosing the metric should be clarified. Note that 0 marks will be given if only results are given but no explanation of experimental settings in the report.
Part 3-3-2: Discussion You are also required to compare the results of different models, and analyse the results (e.g., the reason that the main outperforms baselines).

Part 4 – Conclusion (5 Marks)
Provide a brief summary of the work done and discuss the limitations and potential improvements.
 
 
Report presentation and language (10 Marks)
The report should be presented in a professional manner with a neat and clear layout and all writing in proper English using good grammar.

The report must be written using the following Latex template (make your own copy to work on):
•	URL: https://www.overleaf.com/read/hbqfxbwkrrys
To obtain full marks your report should adhere to the following:
•	Follow the template page layout (Latex):
o	No changes to font type, size or colour 
o	No changing the title of the report and page layout (e.g. margin, orientation, size) 
o	Text should be split into sections with titles and proper paragraphs 
•	Images should be properly cropped and at an appropriate size and resolution. 
•	Correct spelling, punctation and grammar should be used in any text. 
•	Marks may also be removed at markers discretion for other issues with presentation not listed above. 
•	You should not include any screenshots of your code or the loaded data.
 
Python Code
You should implement a solution to the above task all within a single Python Notebook using Google Colab. Any data shown in the text/tables or images used in your report should be generated using this Python Notebook.
This source code must also be provided as both an downloaded notebook (.ipynb) and exported as a PDF from Google Colab.
Markers should be able to run your provided code without any errors requiring debugging. If they are unable to reproduce any results in your report, you will be docked marks for that section.
However, the markers may not actually view your source code, and will only do so if they feel they need to test or otherwise check something. Your marks are based on the report and not the code, so ensure that everything required to complete the tasks are in the report. Even if your code provides a good solution, anything not shown/explained in the report will not be marked.


Deliverables
The following two files should be uploaded using the appropriate Moodle link:
•	A PDF report (exported from Latex)
•	A zip file containing
a.	Your supporting source code in Python Notebook format (.ipynb) implemented using Google Colab
b.	A PDF copy of this source code downloaded from Google Colab
