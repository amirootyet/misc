# CSE 231 Project Guidelines

Congratulations on being chosen to create a 231 project. Please pay heed to these **guidelines** while creating your project. These guidelines are derived from observing 231 projects over a course of several years and will help you formulate better projects that the students, instructors, and the TAs enjoy.

## Project complexity

So you want to design a *cool* project? That is great! We love to see unique, innovative ideas for projects that are entertaining! However, we have learned that projects can get too complicated for 231 students quickly. Please do avoid making projects that are overly complicated or "fragile". While creating your project, please ensure that a typical 231 student will not get bogged down with unnecessary complexity for the sake of an entertaining and cool project. For example, a project might be doing some web scraping and that's great but if the website that the project is scrapping ends up changing even slightly without warning, the project will fail to run maybe a day before due date causing unnecessary problems for TAs and instructors (this has happened before!). If you are a new TA or otherwise unsure if a project might be too hard for 231 students, please consult a seasoned TA or, preferably, the instructors.

## About imports

All projects should `import` libraries (modules) that are already present in Anaconda. If you are using a graphics package or similar in your project, please run the project on the latest Anaconda Spyder installation on at least two operating systems (Mac and Windows) to ensure it functions as expected. For example, Turtle was discovered to frequently crash in Spyder during a semester. Proper testing of the project prior to release saves students and TAs countless hours during help-rooms.

## Processing time
Your project might be using some data file(s). In this case, you need to be aware if any edge cases exist in your project data. It is alright to take real-world data-sets and do something original with them (e.g. draw graphs and inferences). However, please note that real-world data-sets some times contain a large collection (millions) of data points. This is OK as long as the data processing does not take too long. Mimir will timeout for test cases that take too long to run.

## Edge cases in data

If you are using data-sets, you need to be aware if any edge cases exist in your project data. If there are edge cases, it is alright as long as you go through the data-set carefully and account for all edge cases in the data-set and they are properly handled in your project description. For example, 99.9% of all data points in the data-set contain an expected trend of 'name;value' but a few lines might contain an anomaly (edge case) in the form of 'name value'. Your solution needs to take all edge cases into account (either ignore the lines with the edge cases or process them in a particular way -- both should be described in the project DOCX). With a class of over 700 students, people *will* discover those edge cases after the project is released and we need to be prepared for those. Alternatively, reduce the size of your data-set to a manageable level if you cannot account for all edge cases in the original file.

## Dictionaries and lists

If you are using dictionaries and lists in your project, please ensure that the order of insertion or printing will not matter during automated testing on Mimir. In most cases, please remember to `sort` the dictionary or list at the end of a function. This ensures that no-matter what the order of insertion is, as long as the student's data structure contains the expected data they won't fail the test case. This is because the final sort before `return` will ensure random order, that existed before the sorting, does not matter.  

## Difficulty progression

Please think about the natural progression of difficulty in projects. Project should progress naturally in complexity for 231 students. This means project 2, introducing conditional and loop statements, will be slightly more difficult than project 1 and so on. Avoid introducing projects that increase several levels in difficulty when compared to the previous project. This can be hard to keep track of hence it will help if you look up previous project specifics. For example, if you're doing project 2 and the previous project, project 1, hasn't introduced functions yet and your project is introducing functions, avoid making it too complicated with too many functions. Ask instructors if not sure.


## Keep sight of the goal

Projects are meant to demonstrate specific python concepts: dictionaries, lists, classes etc. Keep focused on the objective of your project *at all times*. For example, if the project is focused on introducing conditional statements and loops to students, but contains unnecessary details with a graphics package such that students get bogged with the specifics of the graphics package, it takes the focus away from conditional statements and loop that we were meant to teach in that project. The **focus of your project should be the Python concept it is meant to teach**, not details of how to operate the graphics package.

## Double check your DOCX

Double check (and triple check) your project DOCX submission for errors. During the course of writing your project, you will likely update or modify your project, and your PDF, several times. This introduces inconsistencies. Ensure that your check that your DOCX corresponds to the submitted model solution. Reviewers for the projects need to ensure that the PDF was updated correctly if instructors introduced modifications into the project after it was originally submitted by a TA. 

## Function descriptions

Please ensure your function descriptions, among other things, in the project very clearly explain expectations regarding what is needed. What is the input (parameters) to the function? What is the output (`return`) from the function? Is there potential for an average 231 student to misunderstand or  have questions regarding what is needed in the function? Double check to avoid ambiguities and omissions in the project PDF while describing what is needed.
