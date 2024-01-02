Introduction:
My software project is about “Recipe sharing platform” which requires multiple functionalities and user-specifications including search engine, recipes form for user-submission, login form, sign-up form, and admin dashboard.

Functional & Non-functional Requirements:
1.	The functionalities required me to design a search engine in which the user will enter a string which will be matched with the ingredients list and recipe’s title hence the optimized results will be fetched accordingly from databases. To solve the problem, I declared a component and designed an input area to enable the user enter the string and search for the recipe. According to my program, If the entered string doesn’t match any data from the API, “Not Found” will be printed on screen otherwise the cards of the best solutions will be displayed on screen.
2.	When the user will click on “Sign up” button, it will navigate to sign up form where the users will enter the details and all the user-submitted records will be saved in the “Sign up” database.
3.	When the user click “Logout” form, it will be logged out of the website and redirected to “Login” Form.
4.	When the user click “Login” button, the user entered details will be matched with the records in database and the user will be logged in.
5.	When the user clicks on any “Recipe link” in the header, It will be redirected to recipe page in which all the recipes saved in our databases will be displayed on our recipe page. Upon clicking a particular recipe tab, the full recipe detail of that recipe will be displayed.
6.	In the admin dashboard, all the details of the users, recipes are displayed
7.	In the recipes page in the dashboard, the admin can view all the records of the recipes saved in the database. Not only that, the admin can also add new recipes in the database directly from admin dashboard and also delete the recipe records.
8.	In the Users page in dashboard, the admin can view details of all the details who have registered on the website.
9.	There is also a page on the website where the admin can view all the user’s written commnets.
Problem Statement & Problem Solution:
The problem I faced during the development is that upon entering the keyword in the search bar on the index page, It was difficult to display the results on the same index on which the user has search for a recipe due to the styling issues. To resolve the issue, I designed another page named “Search page” to displayed all the records from the database. To enhance the user experience, I also created another search bar on the same page.
Another difficulty I faced was taking the file input from user on the “Add recipe” Page. To resolve the issue, I used conditional statements (If-else) display the error if the system faces any issues to add the reciepes and asking to perform the action again.

Constraints:
The constraints of this website is that the we cannot take the review or feedback of this website from user. The user can only rate the recipes on the website and not the website itself.
