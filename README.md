# capstoneproject1
Guidelines: You will use the following technologies in this project: Python/Flask, PostgreSQL, SQLAlchemy, Heroku, Jinja, RESTful APIs, JavaScript, HTML, CSS. Depending on your idea, you might end up using WTForms and other technologies discussed in the course.

# Outline: 

 - Team building page for hiring managers, team leads, project managers, team trainers, human resource liasons, etc. 
 - User creates an account with name, email, organization, position and is assigned a numeric code.
 - User can choose 1 of 3 form links to send to 1) a potential team member, 2) a newly hired team member 3) a current team member along with user code.
 - Team member follows link and inputs name and user code, answers questions on form.
 - Data from form is sent to this api https://www.ibm.com/watson/services/personality-insights/
 - Results are recorded in team member's database profile and associated to user using the user code. See schema.
 - Results given to user will give personality strength insights. User can use this information to write interview questions for potential team members,
 assign training/team building activities appropriate to tm's strengths, or use for team building and leadership training for current team members. 

 
