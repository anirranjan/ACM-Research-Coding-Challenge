# ACM Research Coding Challenge (Fall 2020)

## No Collaboration Policy

**You may not collaborate with anyone on this challenge.** You _are_ allowed to use Internet documentation. If you _do_ use existing code (either from Github, Stack Overflow, or other sources), **please cite your sources in the README**.

## Submission Procedure

Please follow the below instructions on how to submit your answers.

1. Create a **public** fork of this repo and name it `ACM-Research-Coding-Challenge`. To fork this repo, click the button on the top right and click the "Fork" button.
2. Clone the fork of the repo to your computer using . `git clone [the URL of your clone]`. You may need to install Git for this (Google it).
3. Complete the Challenge based on the instructions below.
4. Email the link of your repo to research@acmutd.co with the same email you used to submit your application. Be sure to include your name in the email.

## Question One

![Image of Cluster Plot](ClusterPlot.png)
<br/>
Given the following dataset in `ClusterPlot.csv`, determine the number of clusters by using any clustering algorithm. **You're allowed to use any Python library you want to implement this**, just document which ones you used in this README file. Try to complete this as soon as possible.

Regardless if you can or cannot answer the question, provide a short explanation of how you got your solution or how you think it can be solved in your README.md file.

Nirranjan Akilan - ACM Research Coding Challenge solution:
I used the pandas library to read in the CSV file, scikit library to use KMeans, and matplotlib to display my findings. I was able to get to my solution by using the Elbow Method, a method that uses k means for a range of values and calculates the error for each value. The value that results in the shape of the elbow would be the number of clusters in the given dataset. (Source for Elbow Method code: https://stackoverflow.com/questions/19197715/scikit-learn-k-means-elbow-criterion#:~:text=Elbow%20Criterion%20Method%3A,of%20squared%20errors%20(SSE).)
