1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
    Ans- The relationship between the "Product" and "Product_Category" entities is a one-to-many relationship. 
     This means that while one product category can have multiple products associated with it, each product belongs to only one category.
     this relationship is facilitated by the "category_id" field in the "Product" table. This field serves as a foreign key, referencing the "id" field in the "Product_Category" table. 
     Essentially, each record in the "Product" table can be linked to a specific category record in the "Product_Category" table through this field.

2. How could you ensure that each product in the "Product" table has a valid category assigned to it?
   Ans- To ensure that each product in the "Product" table has a valid category assigned to it, you can utilize a foreign key constraint in your database schema. 
     By defining a foreign key constraint on the "category_id" column of the "Product" table, you enforce referential integrity between the "Product" and "Product_Category" tables.
