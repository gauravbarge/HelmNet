Business Context
Workplace safety in hazardous environments like construction sites and industrial plants is crucial to prevent accidents and injuries. One of the most important safety measures is ensuring workers wear safety helmets, which protect against head injuries from falling objects and machinery. Non-compliance with helmet regulations increases the risk of serious injuries or fatalities, making effective monitoring essential, especially in large-scale operations where manual oversight is prone to errors and inefficiency.


To overcome these challenges, SafeGuard Corp plans to develop an automated image analysis system to detect whether workers are wearing safety helmets. This system will improve safety enforcement, ensuring compliance and reducing the risk of head injuries. By automating helmet monitoring, SafeGuard aims to enhance efficiency, scalability, and accuracy, ultimately fostering a safer work environment while minimizing human error in safety oversight.
Objective
As a data scientist at SafeGuard Corp, you are tasked with developing an image classification model that classifies images into one of two categories:
- With Helmet: Workers wearing safety helmets.
- Without Helmet: Workers not wearing safety helmets.


The ultimate objective is to prepare the model for deployment as part of an automated monitoring system. This system will enable real-time analysis of images and assist in ensuring compliance with workplace safety regulations.
Data Dictionary
The dataset consists of 4125 images, equally divided into two categories:


- With Helmet:3161 images showing workers wearing helmets.
- Without Helmet: 964images showing workers not wearing helmets.


Dataset Characteristics:
- Variations in Conditions: Images include diverse environments such as construction sites, factories, and industrial settings, with variations in lighting, angles, and worker postures to simulate real-world conditions.
- Worker Activities: Workers are depicted in actions such as standing, using tools, or moving, ensuring robust model learning for various scenarios.
Important Note
Please set the runtime to T4-GPU in Google Colab. Please follow the below instructions to the runtime toT4-GPU 
Click on "Runtime" in the menu bar
Select "Change runtime type" from the dropdown menu
In the "Hardware accelerator" section, choose "GPU"
You may see multiple GPU options; choose "GPU" if you specifically want a T4 GPU
After selecting the GPU option, click on the "Save" button
Submission Guidelines
There are two ways to work on this project:
i. Full-code way: The full code way is to write the solution code from scratch and only submit a final Python notebook with all the insights and observations.
ii. Low-code way. The low-code way is to use an existing solution notebook template to build the solution and then submit a business presentation with insights and recommendations.
The primary purpose of providing these two options is to allow learners to opt for the approach that aligns with their learning aspirations and outcomes. The below table elaborates on these two options.
Submission type
Who should choose
What is the same across the two
What is different between the two
Final submission file [IMP]
Submission Format
Full-code
Learners who aspire to be in hands-on coding roles in the future focussed on building solution codes from scratch
Perform exploratory data analysis to identify insights and recommendations for the problem 
Focus on code writing: 10 - 20% grading on the quality of the final code submitted
Solution Python notebook from the full-code template submitted in .html format
.html
Low-code
Learners who aspire to be in managerial roles in the future - focus on solution review, interpretation, recommendations, and communicating with business
Focus on business presentation: 10 - 20% grading on the quality of the final business presentation submitted
Business presentation in .pdf format with problem definition, insights, and recommendations
.pdf



Please follow the below steps to complete the assessment.Kindly note that if you submit a presentation, ONLY the presentation will be evaluated. Please make sure that all the sections mentioned in the rubric have been covered in your submission.
i. Full-code version
Download the full-code version of the learner notebook.
Follow the instructions provided in the notebook to complete the project.
Write down insights and recommendations for the business problems in the comments.
Submit only thesolution notebook prepared from the learner notebook [format: .html]
ii. Low-code version
Download the low-code version of the learner notebook.
Follow the instructions provided in the notebook to complete the project.
Prepare a business presentation with insights and recommendations for the business problem.
Submit only thepresentation [format: .pdf]
2. Any assignment found copied/plagiarized with other submissions will not be graded and awarded zero marks.
3. Please ensure timely submission as any submission post-deadline will not be accepted for evaluation.
4. Submission will not be evaluated if
it is submitted post-deadline, or
if more than 1 file is submitted.
Best Practices for Full-code Submissions
The final Python notebook should be well-documented, with inline comments explaining the functionality of code and markdown cells containing comments on the observations and insights.
The notebook should be run from start to finish sequentially before submission.
It is important to remove all warnings and errors before submission.
The notebook should be submitted as an HTML file (.html) and NOT as a notebook file (.ipynb).
Please refer to the FAQ page for common project-related queries.
Best Practices for Low-code Submissions
The presentation should be made keeping in mind that the audience will be the Data Science lead of a company.
The key points in the presentation should be the following:
Business Overview of the problem and solution approach
Key findings and insights that can drive business decisions
Business recommendations
Focus on explaining the key takeaways in an easy-to-understand manner.
The inclusion of the potential benefits of implementing the solution will give you the edge.
Copying and pasting from the notebook is not a good idea, and it is better to avoid showing codes unless they are the focal point of your presentation.
The presentation should be submitted as a PDF file (.pdf) and NOT as a .pptx file.
Please refer to the FAQ page for common project-related queries.
Power Ahead!
Rubric
CriteriaData Overview- Load the dataset 
- Check the shape of the dataPoints3
CriteriaExploratory Data Analysis- Plot random images from each class and print their corresponding labels 
- Check for class imbalance
- Key meaningful observations from EDAPoints6
CriteriaData Pre-processing- Split the data into train, validation, and test 
- Apply the normalizationPoints3
CriteriaConvolutional Neural Network (CNN) from Scratch- Define the Model
- Define the configuration (loss function, optimizer, epochs, batch size)
- Train the Model
- Check and comment on the performance of the modelPoints8
CriteriaTransfer Learning with VGG-16 (Base)- Define the Model
- Define the configuration (loss function, optimizer, epochs, batch size)
- Train the Model
- Check and comment on the performance of the modelPoints8
CriteriaTransfer Learning with VGG-16 (Base + FFNN)- Define the Model
- Define the configuration (loss function, optimizer, epochs, batch size)
- Train the Model
- Check and comment on the performance of the modelPoints8
CriteriaTransfer Learning with VGG-16 (Base + FFNN + Data Augmentation)- Define the Model
- Define the configuration (loss function, optimizer, epochs, batch size)
- Train the Model
- Check and comment on the performance of the modelPoints8
CriteriaModel Performance Comparison and Final Model Selection- Compare the performance of all the models built
- Choose the best model from the ones built with proper reasoning
- Check and comment on the performance of the final model on the test setPoints4
CriteriaActionable Insights & RecommendationsConclude with the key takeaways (actionable insights and recommendations) for the businessPoints4
CriteriaPresentation/Notebook - Overall quality- Structure and flow
- Crispness
- Visual appeal
- Conclusion and Business Recommendations

OR

- Structure and flow
- Well commented code
- Conclusion and Business RecommendationsPoints8

