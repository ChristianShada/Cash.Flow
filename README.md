# Cash&nbsp;Flow<br>
## <b>Purpose:</b> <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To automate a current process of generating a projected cash flow report to Accounting and Finance (on 15th and 30th of every  month). Currently, the report has being generated via Excel by manually updating the loans that will be funded/ drawn in addition to a weekly (Monday)  email notifying Finance/Accounting  of upcoming closings. New automated report will be very similar to Secondary Market report, generated daily.<br>

## <b>Process:</b><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As the information was all on one Excel sheet, I found it difficult to understand and digest from a visual and manipulatable stance. I started by cleaning the data and getting it into individual pages within Excel to make them more manageable. Once this was done I created a Cash Flow project within PowerBI to extract the date in order to manipulate it in such a way that it woudl instantaniously let us know when loans would closing based on the parameters we give it. The data that would allow us to see upcoming loans that would be funed/drawn given any year, quarter, month, and day.

## <b>Challenges</b> 
* Not knowing what the information looked like prior to the excel document - There might be opportunity to go from one report right to the next without needing to create an Excel document.
* The confines of the report are limited to a small amount of time, so the results only show a small snapshot of time.

## Report Layout
### Monthly View of Draw Amounts<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Monthly View Reports allows the users a stagnant view of what is projected within the upcoming months based on the given information or what has been reported.<br><img align="left" img width="500" height="300" alt="dec_temps" src="https://github.com/ChristianShada/Cash.Flow/blob/main/Monthly_View_of_Draw_Amounts.PNG">

<br><br><br><br><br><br><br><br><br><br><br><br>
### Loans in Funding, closing, and in Packagaing or Entry

The next three pages of the report will allow the user to choose any week within the scope of the study or time reported and drill in to what is expected fom what one could see on any given year, down to the direct date that they would want information from. This would be done using the date field on the left side. Once the dates have been identified, the graphs will adjust based on the criteria they have been given.
<img align="left" width="500" height="300" alt="mar_temps" src="https://github.com/ChristianShada/Cash.Flow/blob/main/Loans_in_funding.PNG">

<br><br><br><br><br><br><br><br><br><br><br><br>
## Opportunities
Given the opportunities we could forshadow our numbers based on the different reports that we can pull from NLS and how we can skip the step of loading the report into Excel and right into BowerBI using coding languages like Python through Jupyter Notebook.
