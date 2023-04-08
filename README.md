**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:      |  13 |
| -------------- | --- |
| Student Names: | David Tran    |
|                | Bismarck Leung    |
|                | Chachi Han    |
|                | Zirui Wang    |

# Introduction
For this lab, our group was tasked to familiarize ourselves with realiability assessment tools such as C-SFRAT and the Reliability Demonstration Chart. As part of this, we will learn how to use failure reliability growth testing to help analyze a product's change overtime. Additionally, the analysis of failure data can aid in its future prevention. 


# 

# Assessment Using Reliability Growth Testing 

## Results from Model Comparison
For this portion of the assignment, we had to select the 2 best models using the provided datasets. For this portion of the lab, we used dataset 2 and C-SFRAT. Note that because we're using C-SFRAT, we had to convert the given data to the correct format first. 

We first selected all possible comparisions with the covariates. 
![](./media/all_models.png)

Although finding the model that best fits the data could be done through visual inspection, a more standardized approach such as comparing the log-likelihood will be taken instead. To do this, we will enter the Model Comparison tab and sort by Log-Likelihood. 

![](./media/log_likelihood.png)

Through this analysis, we're able to see that S and TL most closely matches our data. 

# Assessment Using Reliability Demonstration Chart 

# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed
To start, we all installed the necessary tools for this lab and made sure each member of the team knew how to use each tool. We then split into 2 groups, with Bismarck and David working on Part 1, and Chachi and Zirui working on Part 2. For Part 1, we started by trying SRTAT, but we eventually transitioned to using C-SFRAT despite requiring to convert the files to csvs because we found it easier and more elegant to use. Then, omce all the necessarily data was ran through the tools, we all worked together to compile this lab write-up.
# 

# Difficulties encountered, challenges overcome, and lessons learned
With this lab, a difficulty that we encounter was the incompatibility with MacOS that some of the software had. Of course, this eventually led us to adopt C-SFRAT for the visualization and analysis of the data. However, there was also another challenge that arose with adopting C-SFRAT, and that's the format it required. None of the given data files worked with C-SFRAT by default and required us to convert it by hand ourselves. While this help us hone our data analytic skills more this was a major drawback for a while.
# Comments/feedback on the lab itself
