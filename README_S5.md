# This is the Assignment Deliverable for session 5. We look at importing some advanced libraries in this assignment.

We examine the manipulation of files and folders location here. There are 3 exercises which test our application of json, re, pickle and datetime libraries.
Reusing the same annotations we work with in the previous session, we answer the following items using the libraries learnt in this session: 

1. How many annotations you have per month and year. Which month has more annotation files.
2. Create a dictionary where each **key** is a month, and the corresponding **value** is a list containing all the annotation names with where their date corresponds to the month. 
    a. Save it following the json format, and load it again to check that everything is ok.
    b. Save it this time using Pickle.
    c. Instead of storing a list of all the annotation names happening that month, let's create for each annotation a dictionary with keys: name and date (using a datetime object).
3. Print all the annotations from the oldest ones to the newest one during the second half of the 2024. 

# Installation of required modules

```
pip install -r requirements_S5.txt
```

This assignment is about the annotation of satellites which follows a naming convention of the following in a text file, similar to session 4.
{DATE}_{TIME}_SN{SATELLITE_NUMBER}_QUICKVIEW_VISUAL_{VERSION}_{UNIQUE_REGION}.txt

Legend:

- DATE expressed as YYYYMMDD (year, month and day), e.g. 20241201, 20230321 ...
- TIME expressed as HHMMSS (hour, minutes and seconds), e.g. 2134307
- SATELLITE_NUMBER an integer that represents the satellite number.
- VERSION provides the version of the pipeline, e.g. "0_1_2", "1_3_1" ...
- UNIQUE_REGION provides a unique location in the form of a string, e.g SATL-2KM-10N_552_4164

Attached answers are in Session_5_Assignment ipynb file
