Download Link: https://assignmentchef.com/product/solved-cse5243-homework-1-exploratory-data-analysis
<br>
<strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Objective: </strong><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">In this lab, you will analyze the “Adult” dataset available at the </span><a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://archive.ics.uci.edu/ml/datasets/Adult">UCI Machine</a> <a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://archive.ics.uci.edu/ml/datasets/Adult">Learning repository</a><a style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;" href="https://archive.ics.uci.edu/ml/datasets/Adult"><strong>.</strong></a><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;"> In particular, you will concentrate on the first three phases of the CRISP-DM process model – </span><em style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Business Understanding, Data Understanding, </em><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">and </span><em style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Data Preparation. </em><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;"> </span>

The objective of this assignment is two-fold. First, by analyzing and thinking critically about the data, you should identify interesting trends and patterns. Second, the final dataset that you create will be used to build classification models in a later homework assignment.

<strong>Approach:</strong>

<ol>

 <li><strong>Business Understanding Phase</strong>: Write a paragraph providing an overview of the data. Some questions you should consider are: Where did the data come from? What do the rows represent? Why and how was the data collected? What types of questions might you be able to analyze with this data?</li>

</ol>

You should review the dataset description information on the webpage to get some context. Of course you will only have limited background on this topic (and I don’t expect you to become an expert in the census), so do your best to imagine the context for the work, making reasonable assumptions as appropriate. At this stage, you are not analyzing individual attributes, but discussing the dataset in aggregate.

<ol start="2">

 <li><strong>Data Understanding Phase</strong>: Perform exploratory data analysis of the dataset by looking at individual attributes and/or combinations of attributes. You should focus on identifying and describing interesting observations and insights that you might uncover from the data.

  <ol>

   <li>Describe the meaning and type of data for each attribute</li>

   <li>Provide basic statistics for the attributes – e.g., counts, percentiles, mean, median, standard deviation. The statistics should be relevant for the type of attribute.</li>

   <li>Visualize the most important or interesting attributes using appropriate techniques. For each visualization, provide an interpretation explaining why it is appropriate or interesting. What does each visualization tell us?</li>

   <li>Verify data quality: explain any missing values, duplicate data, or outliers. What, if anything, do you need to do about these? Be specific.</li>

   <li>Explore the relationships among the attributes, excluding the class attribute. Use scatter plots, correlation matrices, cross-tabulations, group-wise averages, or other appropriate techniques. Explain and interpret any interesting relationships.</li>

   <li>Identify and explain any interesting relationships between the class attribute and the other attributes. You may refer to earlier visualizations or create new ones.</li>

  </ol></li>

</ol>

You should not simple provide the basic EDA information for all attributes in the data. Instead, you should focus on those that are more interesting or important, and provide some discussion of what you observe.  Pay particular attention to potentially interesting bivariate (two-variable) relationships, as well as the relationship between each attribute and the class.

<ol start="3">

 <li><strong>Data Processing Phase:</strong> Based on the insights gleaned in the <em>data understanding phase, </em>determine what type of processing that you would like to do to create a final dataset to be used for future modeling.

  <ol>

   <li>What attributes do you decide to keep or remove? Please justify.</li>

   <li>Did you decide to implement any attribute transformations? If so, why?</li>

   <li>Did you decide to create any new features? If so, why?</li>

   <li>Implement any data cleaning steps previously identified, and show the effects of that cleaning through the use of appropriate statistics and/or visualizations.</li>

  </ol></li>

</ol>

One of the final outputs of your program should be the creation of a dataset (can be in the format of a data frame) which has all of the attributes you would like to use for the <em>modeling</em> phase of a project, as well as dealing with any outliers, noise or missing values.

<strong>Collaboration: </strong>For this assignment, you should work as an individual. You may informally discuss ideas with classmates, but your work should be your own.

<strong>What you need to turn in:</strong>

<ul>

 <li><strong>Code</strong> – please submit to Carmen any code that you used to process and analyze this data. You do not need to include the input data.</li>

 <li><strong>Written Report</strong>

  <ol>

   <li>The report should be well-written. Please proof-read and remove spelling and grammar errors and typos.</li>

   <li>The report should discuss your analysis and observations. Present charts and graphs to support your observations. If you performed any data processing, cleaning, etc, please discuss it within the report.</li>

   <li>The written report can be in the form of a Python or R Notebook or as a Word or PDF Document.</li>

  </ol></li>

</ul>

<strong>Grading Criteria:</strong>

<ol>

 <li><strong>Overall readability and organization of your report (30%) </strong>– is it well organized and does the presentation flow in a logical manner; are there many grammar and spelling mistakes; do the charts/graphs relate to the text, etc…</li>

 <li><strong>Business Understanding Phase (10%)</strong> – Did you provide a reasonable level of overview information?</li>

 <li><strong>Data Understanding Phase</strong> <strong>(40%) </strong>– Did you find novel and/or interesting insights, or did you solely focus on simple summarizations of the data? Did you draw and present potential conclusion or observations from your analysis of the data? Did the statistics and visualizations used make sense in the context of the data?</li>

 <li><strong>Data Processing Phase (20%)</strong> – Did your program produce the desired output dataset, implementing the preprocessing steps that you outlined in the data processing phase? Have you justified why you eliminated certain features or examples, or included new features?</li>

</ol>

<strong>How to turn in your work on Carmen:</strong>

Please do this work in either Python or R. All the related files (code and/or report) except for the data will be tarred in a *.zip file or *.tgz file, and submitted via Carmen. Use this naming convention: “Project1_Surnames_DotNumber.zip” or

“Project1_Surnames_DotNumber.tgz.”  The submitted file should be less than 5MB.