<h1>Insurance Calculator</h1>


<h2>Description</h2>
You are an employee of Cardinal Insurance, an upcoming insurance company with the goal of insuring incoming and current students at the University of Louisville. You are tasked with creating a calculator that clients can use to calculate the yearly price of their policies. Cardinal Insurance offers two types of insurance: Health and Car Insurance. Health Insurance has three types of coverages that the client can choose from: EPO, PPO, and HDP. Car Insurance has two types of coverages: Full and Liability. Cardinal Insurance charges clients a base rate unique to each coverage. Below is a chart that shows the insurance, coverages, and base rate of each coverage. 
<br />
<br />
<table border="1">
    <thead>
        <tr>
            <th>Coverage</th>
            <th>Insurance Type</th>
            <th>Base Rate</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>EPO</td>
            <td>Health</td>
            <td>$100.00/Month</td>
        </tr>
        <tr>
            <td>PPO</td>
            <td>Health</td>
            <td>$75.00/Month</td>
        </tr>
        <tr>
            <td>HDP</td>
            <td>Health</td>
            <td>$25.00/Month</td>
        </tr>
    </tbody>
</table>

<table border="1">
    <thead>
        <tr>
            <th>Coverage</th>
            <th>Insurance Type</th>
            <th>Base Rate</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Full</td>
            <td>Auto</td>
            <td>$115.00/Month</td>
        </tr>
        <tr>
            <td>Liability</td>
            <td>Auto</td>
            <td>$60.00/Month</td>
        </tr>
    </tbody>
</table>

<h2>Requirements</h2>
It includes the following requirements:
<br />
<br />
- <b>Age of the client. Use type int. Use TryParse to validate the age.</b> 
<br />
- <b>Manufacture Year of the car. Use type int. Use TryParse to validate the year.</b>
<br />
- <b>Use a Combo Box to list the health and car insurance coverages. You can use the Item property to add the respective strings.</b>
<br />
- <b>Radio Buttons to indicate whether the client smokes and has had an accident in the past year. Use a Groupbox to organize your buttons.</b>
<br />
- <b>Use MessageBox.Show() to indicate that if any of the textboxes, combo boxes, or radio buttons are left blank and to prompt the user to fill them out.</b>
<br />
<br />
<br />
For health insurance, coverage is affected by whether the client smokes.
<br />
<br />
- <b>If the client indicates that they smoke, an extra $30.00 premium is added to the base rate.</b> 
<br />
<br />
<br />
For auto insurance, coverages are affected if the user was in a car accident, if they are younger than 25 years old, and have a car made after 2012.
<br />
<br />
- <b>If the client indicates that they were in a car accident within the past year, their base rate increases by 30%.</b> 
<br />
- <b>Since our research indicates that students under 25 are likely to get into accidents, we add an extra $10.00/month youth premium to their base rate.</b>
<br />
- <b>If the user drives a car manufactured in 2012 or later, we add an extra $15.00/month new car premium to their base rate.</b>
<br />
<br />
<br />
Other requirements:
<br />
<br />
It’s also important to note that the client should be able to select no coverage for either type of insurance and not be charged for it. Also note that the requested output is cost per year, so you will need to multiply the monthly cost by 12.
To validate if any of the calculator’s fields are left blank, use if/else if statements to validate and display the appropriate message box. Remember that you are to display the yearly cost of each type of insurance and the total when making your calculations. They need to be in the currency format and rounded to two decimal places.

<h2>Languages and Utilities Used</h2>
- <b>Microsoft Visual Studio</b>
<br />
- <b>C#</b>

<h2>Environments Used </h2>
- <b>Windows 10 Pro</b>


<h2>Examples</h2>

Example calculation for 24 year old, driving a car built in 2015, with an accident record. <br/>
<img src="https://i.imgur.com/c3mJhBl.png" height="80%" width="80%" alt="Log into Windows"/>
<br />
<br />
Example calculation for 50 year old that smokes, driving a car built in 1999, with no accidents on record.
<img src="https://i.imgur.com/oxW0bPi.png" height="80%" width="80%" alt="dir /r"/>
<br />
<br />
Example with invalid data entered
<img src="https://i.imgur.com/NftfWEU.png" height="80%" width="80%" alt="dir /r"/>
<br />
<br />


<h2>Conclusion </h2>
This calculator, built using Microsoft Visual Studio and written in C#, offers a user-friendly interface that integrates seamlessly with the Windows environment. With its focus on both health and car insurance, it factors in various determinants such as age, smoking habits, car manufacture year, and accident history to provide a precise yearly cost estimation. The system is robust, ensuring all fields are adequately filled and validated while providing clear examples for its potential users. This project encapsulates the fusion of user-centric design with functional efficiency, catering to the unique requirements of Cardinal Insurance's clientele.
