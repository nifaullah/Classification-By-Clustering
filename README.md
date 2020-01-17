# Classification-By-Clustering
Academic Project - Hypothesize and Verify the best classifier via clustering

Data : Absenteeism at work dataset pulblicly provided by the UC Irvine's Machine Learning Dataset repository- https://archive.ics.uci.edu/ml/datasets/Absenteeism+at+work . The database was created with records of absenteeism at work from July 2007 to July 2010 at a courier company in Brazil. In total there're 740 instances & 21 attributes.

Goal: 
  1. Do extensive EDA to find out what are the major factors influencing Absenteeism at Work
  2. Hypothesize the best classifier by clustering data using different clustering algorithms
  3. Develop a model which provides potential high absentee from the attributes
  
Approach: First convert the dataset into a more representative smaller dataset where we can accumulate absentation history by employee, perform EDA to determine the major factors influencing absenteeism at work. further run different clustering algorithms to aprroximately predict the shape and cohesiveness of the data, Now hypothesize a classifier and verify if that's the case. Develop a model which predicts potential absentee from the given attributes.

Major Findings: 
  1. Employees with homes closer to the office tend to be more absent
  2. Employees with homes closer to the office also mostly tend to be absent for smaller durations like 2-4 hours
  3. Hypothesis of Decision Tree to be the best suitable classifier from the other different classifiers learned in the class based on cluster anlysis turns out to be true.
  
  Citation/Acknowledgement: Th analysis is done as a part of requirement of CS 6052 Intelligent Analysis course instructed by Dr. Gowtham Atluri at the University of Cincinnati.
