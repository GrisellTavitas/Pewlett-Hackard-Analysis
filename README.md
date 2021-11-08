# Pewlett-Hackard-Analysis
## Module 7
**Overview of the analysis**

Pewlett Hackard is a large company of thousands of employees, but nowadays the company has to look forward to the future in human resources speaking, since many of its employees beginin to retire in a short time.

So then, the company has to be prepared in two ways:
  - Offering retirement packages to certain people who accomplish determined criteria. 
  - Which possitions need to be filled in the near future?

According to that, the company needs to receive this next information, in order to take the neccesary decisions:
  - The Number of Retiring Employees by Title
  - The Employees Eligible for the Mentorship Program
 
**Results**: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

As a result of the first query we made, we could see that the total numer of "retirement titles" were 133,776. 

![List of retirement employees](https://user-images.githubusercontent.com/90433064/140674171-cf394bff-d01a-44cb-85ea-8bbbf8707257.png)

Nevertheless some people may have more than one title in the table, due to promotions; based on that, we removed the duplicate titles for each employee. As a result we found 90,398 unique values:

![Unique titles](https://user-images.githubusercontent.com/90433064/140675409-aaccdb27-1929-4686-8097-8975af545c2a.png)

In order to make a plan on each department, for the transition of each position, we will need to know how many people of each position are in the list of retirements:

![Number of titles](https://user-images.githubusercontent.com/90433064/140675693-e19767b5-a03d-460b-9ba1-ac79cd2882be.png)

After having the complete numbers of people for each department, who is ready to access to the retirement package; the company wants to start a mentoring program to make the transition as smooth as posible for the production. 

So the number of people who are eligible for this mentorship program is 1,549; according to the last query we made. 

![mentorship elegibility](https://user-images.githubusercontent.com/90433064/140676305-a5937a38-bb02-4a5c-beb0-dce78dc1263c.png)

**Summary**: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."

**How many roles will need to be filled as the "silver tsunami" begins to make an impact?**

As we previously said, as a result of the query that we made, grouping the employees about to retire, per title in the company, we could see that the company will need to supply 90,398 positions, detailed as follows:

  -	29414.- Senior Engineer
  -	28254.- Senior Staff
  -	14222.- Engineer
  -	12243.- Staff
  -	4502.- Technique Leader
  -	1761.- Assistant Engineer
  -	2.- Manager

As a suggestion, it’s critical to have a transition plan specially on the first two categories of titles, since it’s a considerable number of people who are retiring and their work need to be covered.
Besides, there are 2 manager roles that need to be filled as well, which it would be crucial for their correspondent team. 

**Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?**

Definitely, it will be enough since the number of people eligible to receive the mentoring program are only 1,529 vs the 90,398 people ready to be retired and certainly many of them willing to mentor the next generation of the company. In this case it would be a good idea to take into account for the company, to expand the criteria of eligibility to receive the mentorship program with at least one or two more generations of employees, because if the mentorship will focus only in people born in 1965, in 10 years the company will have the same problem. So we could prepare a new query looking for people elegible from two more generations that could be those who were born in 1970, and the second generations could be who were born in 1975. In this way, the company would prevent to have another big impact on the production due to a future retirement tsunami.

But actually another criteria to take into account on the eligibility for the mentorship program, could be the position instead of the birthdate. Based on this criteria, the company qould incentive the skills and the loyalty of the people to the company, not only the age. Which would bring more benefits for allm incluiding the company itself. Se we could prepare a query looking for the people in the next position after those who are about to retire. 
