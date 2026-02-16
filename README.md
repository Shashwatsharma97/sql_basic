
# Project Summary

In this project, we'll be practicing inserting and querying data using SQL. 
On the left are the Tables with their fields. The right is where we will be writing our queries. The bottom is where we will see our results.  

## Step 1

### Instructions

SELECT all the data FROM the artist table.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT * FROM artist;
```

</details>

## Step 2

### Instructions

SELECT the first_name, last_name, and country FROM the employee table.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT first_name, last_name, country
FROM employee;
```

</details>

## Step 3

### Instructions

SELECT the name, composer, and milliseconds FROM the track table WHERE the milliseconds are greater than 299000.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT name, composer, milliseconds
FROM track
WHERE milliseconds > 299000;
```

</details>

## Step 4

### Instructions

SELECT the count FROM the track table WHERE the milliseconds are greater than 299000.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT count(*)
FROM track
WHERE milliseconds > 299000;
```


### 👨‍💻 Author

**Shashwat Sharma**

Feel free to use and modify this project for learning purposes!



