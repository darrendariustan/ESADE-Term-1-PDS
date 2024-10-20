# This is the Assignment Deliverable for session 4. We look at importing some basic libraries in this assignment.

We examine the manipulation of files and folders location here. There are 7 exercises which test our application of os, numpy and glob.
Although up till today, I still really wonder where is the relevance of Data Science when there is no manipulation of hardcore statistics.

# Installation of required modules

```
pip install -r requirements_S4.txt
```

This assignment is about the annotation of satellites which follows a naming convention of the following in a text file
{DATE}_{TIME}_SN{SATELLITE_NUMBER}_QUICKVIEW_VISUAL_{VERSION}_{UNIQUE_REGION}.txt

Legend:

- DATE expressed as YYYYMMDD (year, month and day), e.g. 20241201, 20230321 ...
- TIME expressed as HHMMSS (hour, minutes and seconds), e.g. 2134307
- SATELLITE_NUMBER an integer that represents the satellite number.
- VERSION provides the version of the pipeline, e.g. "0_1_2", "1_3_1" ...
- UNIQUE_REGION provides a unique location in the form of a string, e.g SATL-2KM-10N_552_4164

We then have 7 questions to answer below. Kindly find the interpretation of each question phrasing in my attached .ipynb file, as the natural language used below is subjective.

1. How many files the annotations folder has.
2. How many of them follow the name convention expressed above.
3. How many of annotations you have per month and year. Which month has more annotation files.
4. Create a new annotations folder with multiple folders corresponding to a month.
5. Print all the annotations from the most recent to the oldest one. 
6. How many different satellites there are, how many annotations we have per satellite number, and which one was used in the most recent annotation file. 
7. How many unique regions there are.
