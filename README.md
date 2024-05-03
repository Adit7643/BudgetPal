-----Welcome this is Aditya here ----------


This is a expense tracker website. 


what you have to do?


Firstly, download this repository and create a database in pg admon 4 without this You will not be able to make this applicaiton functional. column names and their data tyes are as follows:-


{


database name - budgetPal,


table name - user_data,


column names-


 id - int,
fname - text,
lname - text,
gender - text,
date_of_birth date,
email text,
password text,
tablename text,
total_bal text,
inage bytea


}

After this do npm i and you are good to go.......


Pictures inside my website
To understand my website i have divided my website into 4 parts
login and signup
dashboard
expense tracker
profile and chat server 

lets start with with the login


![Screenshot 2024-04-26 114139](https://github.com/Adit7643/BudgetPal/assets/116075281/de047cb1-58c6-4872-be48-b94fc5053753)
![Screenshot 2024-04-26 114211](https://github.com/Adit7643/BudgetPal/assets/116075281/848c0ee9-62a5-4927-b854-be927f94bade)
![Screenshot 2024-04-26 114156](https://github.com/Adit7643/BudgetPal/assets/116075281/a156bf97-e475-40a6-990e-ca1b846a07d8)

when you switch to localhost then you will see landing page abd there is getstarted button and clicking on that will initiate a function logger() in which all the background will be blured and signup form will pop out.You can easily switch between login, signup and index page. On creating account you will be redirected to login page and your data will be updated at postgres.After filling the valid credentials you will be redirected to another part of the website that is dashboard.


![Screenshot 2024-04-26 113615](https://github.com/Adit7643/BudgetPal/assets/116075281/1d420ba9-50d2-44f9-a4ee-2507237070c5)


![Screenshot 2024-04-26 113653](https://github.com/Adit7643/BudgetPal/assets/116075281/fd634bb7-6a2b-4d0a-9ab9-9a33e7f5b26f)



![Screenshot 2024-04-26 113723](https://github.com/Adit7643/BudgetPal/assets/116075281/fef8e596-779a-4a1a-bf6b-315765ab15f1)

In this section user can view their recent transactions, bill and payment reminders, income generated and Saved cards. Also there is detailed chart of the monthly spending on your dashboard. I have made that using chartjs. All the income are cards which will scale and you can see all by scrolling that i have built using css overflow property.

