# Efficient Yelp API Calls



## Introduction

Application Program Interfaces (APIs) define a set of rules that make it easy to interact with various third-party applications.  For data scientists, APIs allow us to access data that programmers have made publicly available. Access to APIs is granted only by your unique user 'keys' which help developers track data request metrics (i.e., access frequency, content downloaed, etc).

Even though every API is designed with a set of governing principles in mind, every API you interact with will be different, and some charge a fee to access their data. It is up to the developer who wrote the program to specify the protocols needed to interact with that API, and it is up to you to study that documentation.

APIs are usually web URLs where you can pass information either in the URL or by posting a form to the URL and the server returns Java Script Object Notation (JSON) or other similar data formats. 


## Problem Description

For this challenge, you will be working with the Yelp API to search your favorite city for a cuisine type of your choice.

## Solution Description

1. Extract all of the results from your Yelp API search.

2. Compile the returned results into one dataframe. 

**HINT** Use a 'for' loop to append subsequent results to previous results in the JSON file.

3. Save your returned Yelp API results to a notebook for further analysis. 


**What interesting discoveries did you make about your favorite city?**
