# Online Store Database Task

Your task is to create a database structure for a newly launched standard online store. Specifically, you need to design the schema for the database tables in such a way that the store can operate effectively.

The client has provided the following requirements:

1. **Emails and Successful Orders**: Find all users’ email addresses and the number of successfully completed orders they made (an order is not considered successful if it was returned). Only include users who registered in March 2023.
2. **Products in Stock**: Retrieve the names and quantities of all products that have more than 8 units left in stock.
3. **Top Buyer Information**: Get the information (first name, last name, contact number, and any other relevant details) of the customer who purchased the most products in 2023. If there are multiple such customers, display all of them.
4. **Product Sales Value**: Calculate the total value of products sold in 2023 for each product.
5. **Most Returned Product**: Find the name of the product that was returned the most in 2024. If there are multiple such products, display all of them.
6. **Price Ratio**: Determine how many times more expensive the most expensive product is compared to the least expensive product.
7. **Available Products by Category**: Display the number of available products remaining in stock, grouped by category and product.
8. **Top Locations and Times**: For each product, find the locations with the highest demand (i.e., most purchases) and the time intervals (1-hour ranges: e.g., 12:00-13:00, 13:00-14:00, etc.) during which these purchases were made.

To ensure the client’s satisfaction and earn the maximum score of **15 points**, you must follow these rules:

### File Structure

The task should be implemented in a single `.txt` file in the following strict sequence:

#### Step 1: Schema Creation

Write the script to create all necessary tables and constraints. All objects (tables, columns, constraints) should start with your initials. For example, Solomon Morbeladze should prefix all objects with `smorb_`.

#### Step 2: Data Insertion

Write the script to populate each table with at least 3 sample records.

#### Step 3: Queries

Write the queries to address each of the above-listed requirements.

#### Step 4: Object Deletion

Write the script to drop all created objects, ensuring that no objects are left in the database after execution.

### Important Notes

1. The `.txt` file should allow direct copy-pasting into a database without errors.
2. Ensure the data is normalized/denormalized as appropriate to optimize the database structure. Research and apply normalization/denormalization rules as needed.
3. Add any additional details not explicitly mentioned but necessary for proper functionality. For example:
   - Personal identification numbers should be stored as strings.
   - Names and surnames should be mandatory fields.
   - The overall structure and process should be optimal.

By adhering to these guidelines, the client will be satisfied, and you will maximize your chances of receiving full payment.
