By: &nbsp; &nbsp;Richard Hoehn
Due: &nbsp; April 21st, 2023
Class: MTSU - CSCI 7400 - Assignment 07


Introduction:
This is a simple LR learning application for the Sentiment Analysis exercise in the CSCI 7400 Spring 23 class. The entire application
was created in a Jupyter Notebook with Spark v3.3.2.


How to use:

1.
The most important part is that the datasets available online from UCI (link below) are downloaded
into a "datasets" folder in the root of the Jupyter Notebook app called: "Hoehn_Assingment7.ipynb". Please see the
listed "Folder Structure" section below.

2.
Once files have been copied to the "datasets" folder" you can start the Jupyter Notebook application. Please note that
you will need PySpark installed and setup with the correct path for the application to work.

3.
Start with executing each code cell one at a time starting at the top. Or you can simply run "All"

Conclusions:
The over predicability of the model after training data was listed at ~ 79%

When I ran my own data (just for fun) it predicted at ~ 83% accuracy! Which is really nice
to see that it worked.


Folder Structure:
root
|-- Hoehn_Assingment7.ipynb
|-- Hoehn_Assignment7_readme.txt
|-- datasets
&nbsp; &nbsp; |-- amazon_cells_labelled.txt
&nbsp; &nbsp; |-- imdb_labelled.txt
&nbsp; &nbsp; |-- yelp_labelled.txt


Citations:
The datasets came from: "From Group to Individual Labels using Deep Features', Kotzias et. al,. KDD 2015"