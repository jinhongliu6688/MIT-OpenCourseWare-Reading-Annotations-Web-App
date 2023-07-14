# MIT OpenCourseWare Reading Annotations Web Application

## Project Introduction:
- MIT OpenCourseWare provides free online resources for 2,494 university courses.
- Our project aimed to annotate reading materials from each course syllabus page, categorizing them into required and optional readings.
- We hope the annotations can help self-leaners quickly find important readings related to their topic of interest, and inform instructors with statistics on readings that provide guidelines to designing future curriculums.

## Project Info:
- Website: https://mit-web-application-3d4da2965f8d.herokuapp.com/
- Achievement: Most popular project, voted by the cohort: Rank 1st
- Scrapped data online using Python, BeautifulSoup
- Developed Web Application using Python as Back-end and Javascript as Front-end
- Implemented using numpy, pandas, fastapi, uvicorn, matplotlib, nltk, jinja2
- Deployed Web app using Docker image and Microsoft Azure

## Web App Features:
- In both Search by Title page and Search by Author page, you can search the readings based on different course topics.
  - For Type of Readings, you can choose whether they are Book, Academic Paper, or All to include both of them.
  - For Readings to Include, you can choose whether they are Required, Optional in MIT open courses, or All to include both of them.
  - Please click the Search button after making the selections.
  - If no readings appear, that means no readings match the selections. Please make other selections and try again!
- Please check out our statistics page! There are some visualizations about our annotation progress, average number of readings by major topic, and average number of readings by major topic.
