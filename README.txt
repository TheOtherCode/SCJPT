Hi everyone!

Ever wondered what exactly, AND how much work Supreme Court judges are doing?
More than 4 crore cases pending in all courts of India.
In such a scenario, it is imperative that the work of judges is quantitatively analysed.

This program seeks to fetch and present the amount of work done by present sitting judges in the Supreme Court.
This code access data available on {https://main.sci.gov.in/} and specifically, {https://main.sci.gov.in/daily-order}

Once the data is fetched, the same is presented in a excel sheet.
[Please look at the attached excel sheet, to get a sense of the method of organisation]


I understand this may not be making sense to a lot of people interested.
I will try to soon prepare a dashboard, which will make running/using the code straightforward.
Till then I hope this code is able to help atleast those, who know how to run it.

Disclaimer - 
Having explained the program, it is important I point out that the numbers of 'daily orders' of a judge is not an entirely accurate indicator of a judges' absolute efficiency or productivity. 
Therefore, if you do come across days where judges have passed an unusually small number of orders, do not conclude on the absolute efficiency or productivity of the judge.



For any comments, suggestions, feedback OR in case you may have faced any problem in running the code
get in touch:-

email - talktovedant@proton.me
Hi everyone!

Ever wondered how much work Supreme Court judges are doing?

Being surrounded by news items on important judgments, it often becomes difficult to arrive at a number and quantitatively determine the impact any judge is bringing in the Judiciary.



I have been working on a program that will let us do exactly this... Quantitatively study the impact of a judge.



Find the source code here - https://github.com/TheOtherCode/SCJPT



Brief - 

This program, written in python, will let the user get the exact number of orders any sitting judge of the Supreme Court has passed on any date in his/her entire tenure.

At the moment the program only produces an excel sheet for every sitting judge with two columns - (i) date, and (ii) number of daily orders.



I am making it public right now to receive feedback and comments.

Feel free to get in touch!



What the program does - 

As the final output, the program will produce an Excel Workbook with- 

1. One sheet as a MasterList - holding the names, dates of appointment, and retirement of judges; AND 

2. Additional 34 sheets corresponding to every judge of the Supreme Court.

Sheets for individual judges will hold two columns - A - for date; and B - number of daily orders passed on that date.



How the program runs-

The program prepares an excel workbook. 

Then accesses https://main.sci.gov.in/ to fetch data on - 

(i) Names of sitting judges; Dates of Appointment and Retirement of judges.

(ii) Number of daily orders passed by each judge, on every date in his/her tenure till today.

(iii) The data is then clean and processed and finally pushed onto an Excel Workbook.



In the pipeline - 

1. Dashboard presenting the data in a more user friendly manner. [Might take about a few weeks. Since I might have some learning to do.]

2. Extending the program to sitting judges of other High Courts

3. A deeper analysis of dates falling within first quartile [25th percentile] in 'number of daily-orders' passed.

4. An additional module in the program for fetching number of 'judgments' in addition to 'daily orders'



Disclaimer - 

Having explained the program, it is important I point out that the numbers of 'daily orders' of a judge is not an entirely accurate indicator of a judges' absolute efficiency or productivity. 

Therefore, if you do come across days where judges have passed an unusually small number of orders, do not conclude on the absolute efficiency or productivity of the judge.



However, it is also true that, the cardinal duty of a judge is adjudication. And therefore, the number of cases adjudicated, orders passed is an important factor to be studied.



Make use of the program!



Get in touch if you think I may help:-

email - talktovedant@proton.me
https://linktr.ee/vedantchoudhary
