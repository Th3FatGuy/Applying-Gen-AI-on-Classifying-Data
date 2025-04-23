# Applying-Gen-AI-on-Classifying-Data

Note: The project being used for Kaggle 5-days

## Case scenario:
There are numerous course alternatives available to students within the same major before they enroll in a university, academy, or college. There is a lack of specialized knowledge and skills in real-life jobs, however, resulting from the majority of these courses' shallow instruction, which makes it challenging for students to obtain them. On the other hand, a lack of highly qualified workers for many organizations in emerging nations makes hiring difficult, particularly for senior roles that still need more talent. By using Google Gen AI to categorize data and skill sets, this initiative hopes to assist educational institutions in identifying and improving the specialized skills and tools required in their curricula so that students are better equipped for the workforce. The data which being analyzed will be from Broadcom and will be using model Gemini-2.0-Flash from Google Gemini AI.

## Use case of the project
- Collecting job post from from Broadcom
- Classifying data from job post into different categories

## Further work:
- Ranking the amount of skills appearance: With the dataset, we can create a top ten skills that needs for each jobs in different domains
- CV-recognization: Rating the CV according to the job requirement and finding out which skills he/she needs to upgrade to get the job.

## Setup:
1. Before running the Jupyter Notebook file, create a **ConfigFile.properties** file
2. Inside the config file, insert as follow:
   [URL]
   url.broadcom = https://broadcom.wd1.myworkdayjobs.com/External_Career
   url.chromedriver = *# Download chromedriver then insert the link here*
   [API]
   api.key_googleai = *# Insert the API key from Gemini AI here*

**Note:** The crawling data also apply for some similar career site from MyWorkDayJobs, so you can change the url.broadcom variable to other links from same site.
