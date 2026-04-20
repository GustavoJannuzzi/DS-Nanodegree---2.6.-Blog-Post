# 6. Project: Data Science Blog Post

Created: April 15, 2026 3:33 PM
Tags: Não iniciado

# 6.1.Project Overview

# Introduction

During this project, you will write a blog post that answers the following question from your chosen data set.

Questions:

1. What are the most important features of the data set, what do they mean, and how do they drive the predicted outcome?
2. What unusual, or creative, insights are you able to gather from the data set?
3. How accurate is the model that you have trained to predict the data in the data set?
4. What will happen in a creative, predictive, scenario using the model that you have trained?

The purpose of the project is to show that you understand the information presented to you and can explain it in a clear way to an audience.

# 6.2. Project Dataset Options

# Data

For the project, you will choose data from one of the data sources listed below. Data scientists work in all different domains, so choose the dataset that interests you most!

Your main constraint is that you have only learned how to work with tabular, numeric data so far. You will have the easiest time if you look for CSV datasets that primarily contain numbers. It's ok if you only have a few features and a target variable.

Avoid datasets that are primarily composed of text or image data; working with these data types in scikit-learn is out of scope for this course.

# Tech Careers: StackOverflow Developer Survey [UTILIZAR ESTE]

Visit the [**developer survey homepage(opens in a new tab)**](https://survey.stackoverflow.co/) to download survey results from this year and past years, dating back to 2011. For inspiration, check out some of the [**findings that StackOverflow put together for the 2024 survey(opens in a new tab)**](https://survey.stackoverflow.co/2024/).

# Credit and Economic Data: The World Bank Databank

[**World Bank Databank Website(opens in a new tab)**](https://databank.worldbank.org/)

The World Bank is an institution that provides much needed credit and economic management for countries around the world. As part of their duties, they have comprehensive forms of economic data on their partners.

# History: The Roman Empire Data

[**Project Mercury - Computational Modeling in Roman Studies(opens in a new tab)**](https://projectmercury.eu/datasets/)

The Roman Empire was the world's preeminent center of culture, commerce, and high civilization for thousands of years. Curious archaeologists have compiled comprehensive data on Roman Civilization that we can learn from. Using new, advanced, machine learning tools, be one of the first to analyze data from the Roman Empire and explore Roman Civilization.

# Economic and Business Data: United States of America Business Formation Statistics

[**Business formation statistics - US Census Bureau(opens in a new tab)**](https://www.census.gov/econ/bfs/index.html)

The United States of America is the world's leading economy and uses bureaucratic staff to manage its economic activities. One of these organizations, the Census Bureau of the United States, compiles statistics on new business formation within the country to understand the flow of economic activity.

# Healthcare: Centers for Medicare & Medicaid Services (CMS)

[**CMS dataset search(opens in a new tab)**](https://data.cms.gov/provider-data/search)

The United States CMS is a federal agency that provides health coverage to millions of Americans. Their datasets primarily focus on medical facilities that accept Medicare and Medicaid patients.

# Education: DataShop

[**DataShop landing page(opens in a new tab)**](https://pslcdatashop.web.cmu.edu/)

DataShop is a repository of datasets related to the learning sciences. It is maintained by Cargenie Mellon University.

# 6.3. Project Steps and Instructions

# Key Steps for the Project

Feel free to be creative with your solutions, but do follow the **CRISP-DM process** in finding your solutions.

1. Begin the project by conducting an exploratory data analysis. Common forms of exploratory data analysis include generating distribution plots to understand the skewedness of different variables or generating histograms to understand how data is distributed. Alternatively, some data scientists like to perform principal component analyses to better understand the underlying structure of the data.
2. Next, summarize the findings of your exploration. Explain whether the data needs to be cleaned based on your findings. If it does, perform the data cleaning. If not, move on with selecting the type of machine learning model that is appropriate for predicting from your data.
3. Train the machine learning model on your data. Evaluate the model for overall accuracy, recall, and other evaluation scores. Explain what the measures tell us about the model and how it works.
4. Imagine a new scenario that requires a prediction from your model to answer. Describe the scenario in your post and run a prediction from the model. Explain the meaning of this prediction and what it tells a reader.

# Project Deliverables

There are two **deliverables** that are required for project completion.

- A **Github repository** for your code.
- A **blog post** of your findings.

Your **Github repository** must have the following contents:

- A README.md file that communicates the libraries used, the motivation for the project, the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgments.
- Your code in a Jupyter notebook, with appropriate comments, analysis, and documentation.
- You may also provide any other necessary documentation you find necessary.

For the **blog post**, pick a platform of your own choice. For example, it can be on your website, a Medium post (Josh's sample [**report(opens in a new tab)**](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711) on *How Do YOU Become A Developer?*), or a Github blog post. Your blog** **must provide the following:

- A clear and engaging title and image.
- Your questions of interest.
- Your findings for those questions with a supporting statistic(s), table, or visual.

**Note**: The post should not dive into technical details or difficulties of the analysis; this should be saved for Github. The post should be understandable for non-technical people from many fields.

# Keeping Yourself and Your Reader Motivated

- **Keep your post short and sweet**. Short posts will increase audience engagement, as well as the likelihood you complete the writing of your post. Try to limit your post to 200-500 words.
- **Create an outline.** A useful outline for your post could just include an introduction, each of your questions or takeaways, and then a conclusion. This will help you stay focused when writing your post.
- **Review. Review. Review.** When you think you have reviewed enough, find someone else to review. The more review you have of your work, the better it will become. Also, don't be afraid of posting your unfinished thoughts and questions that you are still pondering.

# Task List

- [ ]  create Github repo
- [ ]  Select plataform for blog post and create account if needed
- [ ]  Create README for github repo
- [ ]  Write code in a jupyter notebook
- [ ]  Push your README and code to the github repo
- [ ]  Write and publish your blog post
- [ ]  Check your work against the rubric to ensure you meet all of the necessary criteria for the project

# 6.4. Environment Setup

# Workspace Instructions

You may use the Workspace below, or a local environment setup, to complete your analysis.

There is no "starter" notebook in the Workspace. Create a new notebook to begin.

Note that you will not be able to submit your project through this Workspace. Instead, you need to push your code to GitHub and publish your blog post to a public platform, and submit those links.

# 6.5. Project Rubric

# Rubric

Use this project rubric to understand and assess the project criteria.

# Code Functionality and Readability

| **Criteria** | **Submission Requirements** |
| --- | --- |
| Code is readable (uses good coding practices - PEP8) | Code has a logical structure and uses comments with markdown effectively. The steps of the data science process (gather, assess, clean, analyze, model, visualize) are clearly identified with comments or Markdown cells, as well. The naming for variables and functions should be according to PEP8 style guide. |
| Jupyter Notebook is executable and correct | All the project code is contained in a Jupyter notebook which can be successfully executed to generate the correct output. |
| Contains code that is well documented and uses formal code conventions | Code is well documented and uses functions and classes as necessary. All functions include document strings. DRY principles are implemented. |

# Data

| **Criteria** | **Submission Requirements** |
| --- | --- |
| Project follows the CRISP-DM Process while analyzing their data. | Project follows the CRISP-DM process outlined for questions through communication. This can be done in the README or the notebook. If a question does not require machine learning, descriptive or inferential statistics should be used to create a compelling answer to a particular question. |
| Proper handling of categorical and missing values in the dataset. | Categorical variables are handled appropriately for machine learning models (if models are created). Missing values are also handled appropriately for both descriptive and ML techniques. Document why a particular approach was used, and why it was appropriate for a particular situation. |

# Analysis, Modeling, Visualization

| **Criteria** | **Submission Requirements** |
| --- | --- |
| There are 3-5 business questions asked and answered. | In the Jupyter Notebook, there are between 3-5 questions asked, related to the business or real-world context of the data. Each question is answered with appropriate visualization, table, or statistic. |

# GitHub Repository

| **Criteria** | **Submission Requirements** |
| --- | --- |
| Student must publish their code in a public Github repository. | Student must have a Github repository of their project. The repository must have a README.md file that communicates the libraries used, the motivation for the project, the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgements. Students should not use another student's code to complete the project, but they may use other references on the web including StackOverflow and Kaggle to complete the project. |

# Blog Post

| **Criteria** | **Submission Requirements** |
| --- | --- |
| Communicate their findings with stakeholders. | Student must have a blog post on a platform of their own choice. The post should communicate the data science performed and provide non-technical summaries that explain the findings. The post should clearly communicate the important inferences of the analyses. |
| There should be an intriguing title and image related to the project. | Student must have a title and image to draw readers to their post. |
| The body of the post has paragraphs that are broken up by appropriate white space and images. | There are no long, ongoing blocks of text without line breaks or images for separation anywhere in the post. |
| Clearly state the business questions and the corresponding solutions. | Each question is clearly stated and each answer includes a clear visual, table, or statistic. |

# 6.6. Submit Project

# Before you submit:

Your project needs to **Meet Specifications** in all categories of the [**Project Rubric(opens in a new tab)**](https://review.udacity.com/#!/rubrics/1507/view) in order to pass. So before you submit, do a self-assessment of your work using the rubric, and you'll probably find some revisions you want to make first.

All you need to submit for this project are **two links** - one for your GitHub repo and one for your blog post. Your GitHub repo should contain your code, dataset, and README.md files.

You can either submit these links in the text input, or you can create a PDF document containing these links and upload it.

**Make sure that your repo and blog post are publicly visible.** We are unable to grade submissions that are not publicly visible!