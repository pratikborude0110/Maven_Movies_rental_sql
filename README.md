# Maven_Movies_rental_sql
Data analysis of movies CD/DVD rental (transactions) and inventory

# Maven Movies Data Analysis: Enhancing Insights for a Rental Business

## Project Overview:
This project analyzes a movie rental business's database to provide actionable insights for improving operations, marketing strategies, and inventory management. The dataset is hosted in the MAVENMOVIES database, and SQL was extensively used for exploratory data analysis (EDA), schema understanding, and answering business-critical ad-hoc queries.

## Project Objectives:

### Customer Insights:

Identify customer details (names, emails) for targeted marketing campaigns.
Analyze customer rental patterns to improve customer engagement.

### Movie Inventory Analysis:

Explore the rental inventory and classify movies based on rental rates and availability.
Provide recommendations for expanding the movie collection based on popularity and rental rates.
Revenue Optimization:

Analyze rental rates to identify trends and the profitability of various pricing categories.
Determine the most rented movie categories and ratings to maximize revenue.

### Operational Efficiency:

Help track and manage movie inventory effectively.
Highlight gaps in the inventory and optimize stock levels.

# Tools & Library Used

# Query Task

## Q1. You need to provide customer firstname, lastname and email id to the marketing team 
![Output_Q1](https://github.com/user-attachments/assets/ad81e9f3-572d-4a9e-b43c-14e3a3aed510)


## Q2. How many movies are with rental rate of $0.99? 
![Output_Q2](https://github.com/user-attachments/assets/3d671386-b756-4c79-9200-ac9ad9fec5c2)


## Q3. We want to see rental rate and how many movies are in each rental category 
![Output_Q3](https://github.com/user-attachments/assets/fc5b7c13-9013-4c38-a0fc-f07102c0437f)


## Q4. Which rating has the most films? 
![Output_Q4](https://github.com/user-attachments/assets/f5bc1611-88bb-4a5f-a334-dfa91af31436)


## Q5. Which rating is most prevalant in each store? 
![Output_Q5](https://github.com/user-attachments/assets/a47c1803-dfe7-4b12-a5b8-68d8f38ae075)


## Q6. List of films by Film Name, Category, Language 
![Output_Q6](https://github.com/user-attachments/assets/7bab406c-a8c3-448e-af99-040a40d99e74)


## Q7. How many times each movie has been rented out?
![Output_Q7](https://github.com/user-attachments/assets/338fc9be-9503-4675-b7e2-ec09db63c987)


## Q8. REVENUE PER FILM (TOP 10 GROSSERS)
![Output_Q8](https://github.com/user-attachments/assets/79771c0c-9a21-4702-8508-9d1ddf859103)


## Q9. Most Spending Customer so that we can send him/her rewards or debate points
![Output_Q9](https://github.com/user-attachments/assets/157d3130-969e-4689-b079-461cd481aab0)


## Q10. Which Store has historically brought the most revenue?
![Output_Q10](https://github.com/user-attachments/assets/9cc17315-9d0e-4a09-b5b7-1a524e9c7e51)


## Q11. How many rentals we have for each month
![Output_Q11](https://github.com/user-attachments/assets/b5f96b66-4b1d-4e04-83d5-8c8887c77444)


## Q12. Reward users who have rented at least 30 times (with details of customers)
![Output_Q12](https://github.com/user-attachments/assets/d3dd9bbc-d6af-49cb-8a4d-cd197a5ad8fb)


## Q13. Could you pull all payments from our first 100 customers (based on customer ID)
![Output_Q13](https://github.com/user-attachments/assets/5d5844a6-76e0-44d2-9e25-64e23de87b4f)


## Q14. Now I’d love to see just payments over $5 for those same customers, since January 1, 2006
![Output_Q14](https://github.com/user-attachments/assets/98a85431-f2e4-4277-bb30-9ff03771acad)


## Q15. Now, could you please write a query to pull all payments from those specific customers, along with payments over $5, from any customer?
![Output_Q15](https://github.com/user-attachments/assets/fb2fde21-99a9-4c37-b57f-b87362b3a0e0)


## Q16. We need to understand the special features in our films. Could you pull a list of films which include a Behind the Scenes special feature?
![Output_Q16](https://github.com/user-attachments/assets/032db75f-754f-4519-ac99-bc2c6c54feb8)


## Q17. unique movie ratings and number of movies
![Output_Q17](https://github.com/user-attachments/assets/be43a2e2-5e64-47bd-be41-003d9d6009b7)


## Q18. Could you please pull a count of titles sliced by rental duration?
![Output_Q18](https://github.com/user-attachments/assets/284c1e7e-5f33-479d-8d41-e5bcad3e7c90)


## Q19. RATING, COUNT_MOVIES,LENGTH OF MOVIES AND COMPARE WITH RENTAL DURATION
![Output_Q19](https://github.com/user-attachments/assets/9071d700-5079-4a01-b15c-d94e19191e63)


## Q20. I’m wondering if we charge more for a rental when the replacement cost is higher. Can you help me pull a count of films, along with the average, min, and max rental rate, grouped by replacement cost?
![Output_Q20](https://github.com/user-attachments/assets/cc88662c-0c6e-499a-9c54-354f0c3a368b)


## Q21. “I’d like to talk to customers that have not rented much from us to understand if there is something we could be doing better. Could you pull a list of customer_ids with less than 15 rentals all-time?”
![Output_Q21](https://github.com/user-attachments/assets/7b799bbf-e371-4524-b0a0-2da423eb6e6b)


## Q22. “I’d like to see if our longest films also tend to be our most expensive rentals. Could you pull me a list of all film titles along with their lengths and rental rates, and sort them from longest to shortest?”
![Output_Q22](https://github.com/user-attachments/assets/dfd0c5f2-345a-4ec4-95be-e76e656a2946)

## Q23. CATEGORIZE MOVIES AS PER LENGTH
![Output_Q23](https://github.com/user-attachments/assets/d3bbd9fe-432d-4f26-969d-5cc400b365e8)


## Q24. CATEGORIZING MOVIES TO RECOMMEND VARIOUS AGE GROUPS AND DEMOGRAPHIC
![Output_Q24](https://github.com/user-attachments/assets/ddffb9a4-3341-4c03-9af0-4da9ed5b391b)


## Q25. “I’d like to know which store each customer goes to, and whether or not they are active. Could you pull a list of first and last names of all customers, and label them as either ‘store 1 active’, ‘store 1 inactive’, ‘store 2 active’, or ‘store 2 inactive’?”
![Output_Q25](https://github.com/user-attachments/assets/0a1ef94c-ef6d-44a8-9a3a-91c2616fff68)

## Q26. “Can you pull for me a list of each film we have in inventory? I would like to see the film’s title, description, and the store_id value associated with each item, and its inventory_id. Thanks!”
![Output_Q26](https://github.com/user-attachments/assets/0b87e824-e3f6-4953-bc80-743873c97cbd)


## Q27. Actor first_name, last_name and number of movies
![Output_Q27](https://github.com/user-attachments/assets/568e3309-205f-4e49-b635-cb8720515871)


## Q28. “One of our investors is interested in the films we carry and how many actors are listed for each film title. Can you pull a list of all titles, and figure out how many actors are associated with each title?”
![Output_Q28](https://github.com/user-attachments/assets/7946fe38-26ff-4978-b11f-d2ae5fc09326)

    
## Q29. “Customers often ask which films their favorite actors appear in. It would be great to have a list of all actors, with each title that they appear in. Could you please pull that for me?”
![Output_Q29](https://github.com/user-attachments/assets/7f4a5959-8339-4033-a0fc-392e5e8f3d6e)


## Q30. “The Manager from Store 2 is working on expanding our film collection there. Could you pull a list of distinct titles and their descriptions, currently available in inventory at store 2?”
![Output_Q30](https://github.com/user-attachments/assets/ec55f504-7d62-4594-aa45-3ab2d832fb2f)



## Q31. “We will be hosting a meeting with all of our staff and advisors soon. Could you pull one list of all staff and advisor names, and include a column noting whether they are a staff member or advisor? Thanks!”
![Output_Q31](https://github.com/user-attachments/assets/1f6d4cac-30d2-43ab-8879-ca7e8697849a)

















