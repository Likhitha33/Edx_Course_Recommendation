# Edx_Course_Recommendation

#  Recommender system of edx course data


**Content Based Filtering**


**What we would like to achieve in this notebook**


1.1 | Problem Formulation/Statement
With the world becoming digital, any new skill can be acquired with just a click. However, many of us still needs a dedicated curriculum in order to excel in a specific topic.

This is where e-learning platforms comes handy and EdX is one of such massive open online course (MOOC) providers.

So we've found a course we like, and went through the course, so what next?

With the availability of so many online courses, it may be take some effort and time to look through all available courses.
We can utilise a recommendation system to give some tips on what course the user might like to go though next
Whilst there are quite a number approaches to recommendation systems, well utilise an approach which requires NLP

1.2 | Recommendation system

GOALS

The purpose of our recommendation system is to inform a user about possible courses they make like, based on a course they liked.


METHOD

We will utilise scrapped course description data (our corpus), well convert each document into vector form using (bow,embeddings), then calculate the consine similarity, from which we will be able to extract courses which are most similar.


1.3 | The Dataset

This dataset is scraped off the publicly available information on the EdX website.
This dataset consists of 720 rows and 6 columns namely Name of the Course, Name of the University, Difficulty Level, Course URL, short summary about the course and course description
What is edX?

edX online courses are self-paced, interactive courses offered by leading universities and organizations around the world. These courses provide learners with a range of topics to explore and learn from, including computer science, business, health, engineering, humanities, and more. With edX courses, learners can gain valuable skills and knowledge in an engaging and convenient way.

Image


1.4 | Notebook Goals

Two subgoals are of interest:

EDA study | Analyse an draw conclusions based on the courses that are available

Course Recommendation system | Create a course recommendation based on a specified course.



2 | idX DATASET

WHAT WE WILL DO IN THIS SECTION

We'll read the data EdX.csv

Lower the register of column names

Show for one course the name, about & description


# Deployment

Also did local deployment.
