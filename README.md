Download Link: https://assignmentchef.com/product/solved-r-assignment-4
<br>
<strong>Question 1</strong>

The data for this question were simulated data for 1000 students taking the same structured standardized exam each month for 3 months such that questions with the same Item Number over time are different but test the same concept.

Each exam had 20 questions worth 5 points each, where each question could be graded 0 (completely wrong) to 5 (completely correct) with different amounts of partial credit in between. You can read in the data from the file attached to this Crowdmark assignment below.

exam_data&lt;-<strong>dget</strong>(“exam.txt”)

Remember that the exam.txt file must be in your current working directory, or you need to specify an alternate path. The dget function reads in data from any R object. In this object, you can clearly acess the data for any student (“Subject ID”) for any question (“ItemNum”) in any month (“Timepoint”).

<ul>

 <li>What class of object is exam_data?</li>

 <li>Using the exam_data object, compute the average overall test score for each month (timepoint). Does it appear that the test is getting more difficult over time?</li>

 <li>Using the exam_data object, compute the overall total (summed) test score for each student (subject ID) for each month (timepoint). Give the list of the five students with the highest scores for each of the three months (timepoints). <strong>Hint: either use sort or convert it into a tibble.</strong></li>

 <li>Using the exam_data object, compute the overall average score for each question (item number) for each month (timepoint). Plot the average scores for each question for each year over time. <strong>Hint: Depending on which function (and package) you use, you may need to convert it to a different class of object.</strong></li>

</ul>