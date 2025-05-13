# csci-ga-2433-011-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [CSCI-GA.2433-011 Homework 2 Solved](https://www.ankitcodinghub.com/product/csci-ga-2433-011-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93524&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI-GA.2433-011 Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
See https://cims.nyu.edu/webapps/content/systems/userservices/databases for instructions on how to set up MySQL database on CIMS. I recommend using “self- administered MySql database” (https://cims.nyu.edu/webapps/content/systems/userservices/databases-selfmanaged)

For this assignment, you are to create a database (using MySQL) with the following tables with the data as follows.

Employee(Name, Salary, Manager, Department) Smith, 31000, Jones, Switch

Patten, 28000, NULL, Software Hughes, 33000, Jones, Switch Jones, 32000, Patten, Switch Warren, 40000, Patten, Software

Key is Name.

Course(Student, Subj, Prof, Grade) Smith, Algs, Hackett, 85

Patten, Algs, Hackett, 80 Patten, Comp, Roe, 70 Jones, Comp, Roe, 75 Jones, Dbase, Black, 80 Warren, Dbase, Black, 75 Warren, Comp, Roe, 65

Key is Student, Subj.

Write all your SQL queries in one script (text) file and submit the script file (see above). The script file (text format) simply lists all the SQL queries you have as answers for the problems below (separated by semicolon, certainly). Aside from reading your answers, we will run the script file on several similar but different databases (modified from the example data above. Remember: a query does not just work on one instance of the database!). Hence your script file should be runnable from MySQL directly, for example, from mysql prompt as follows:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
mysql&gt; source scriptfile.sql Each query is worth 10 points.

<ol>
<li>Find names of all employees who work in the software department. On above example data, should be Patten and Warren.</li>
<li>Find names of all employees who earn at least 5000 more than their managers. On above example data, should be Warren.</li>
<li>Find names of all employees who received higher grades than their managers in the same course. On above example data, it should be Jones.</li>
<li>Find name of all employees who do not take any class. On above example data, should be Hughes.</li>
<li>Find departments in which all of their employees take (one or more) courses. On above example data, it should be Software. Hint: it’s fine to use temporary tables.</li>
<li>Find departments in which all of their employees take two or more courses. On above example data, it should be Software. Hint: it’s fine to use temporary tables.</li>
<li>Find the average salary earned. On example data should be 32,800.</li>
<li>Find the lowest salary earned by people taking Roe’s course. On example data, it
should be 28,000.
</li>
<li>For those departments whose employees (collectively) take more than three
courses, find the average salary by department. On example data, it should be 34,000. Hint: It’s fine to use two queries and a CREATE TEMPORARY TABLE command that finds relevant departments first.
</li>
<li>For each department, find the percentage of the employees who do not take any course. On example data, it should be two tuples “(Software, 0), (Switch, 33.33)”. Note that if all the employees of a department D take courses, then the department should get a result as “(D, 0)”. For example, if your answer on example data is simply (Switch, 33.33) (without (Software, 0)), then your query is wrong. Hint: you may use case function like “Case when C is null then 0 else C/D end” in the Select Clause.</li>
</ol>
General hint: The operation MINUS is not supported by SQL, which can be replaced via “left join”. For example, the following MINUS operation:

Select A From R1 MINUS

Select A From R2;

may be replaced by:

Select A

From R1 left join R2 on R1.A=R2.A Where R2.A is NULL;

</div>
</div>
</div>
