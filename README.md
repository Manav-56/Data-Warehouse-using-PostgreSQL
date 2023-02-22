# Data-Warehouse-using-PostgreSQL
Configured Dimensional Modeling within Data Warehouse 

# Data Warehouse

- A Data Warehouse is a copy of transaction data specially structured for query and analysis. 

## Dimensional Modeling :

In Warehouse Dimensional Modeling use such as Star Schema, Snowflake Schema.
 

### Star Schema vs 3NF Data Model
#### Star Schema
#### Advantages 
- Easy to understand for end users (such as Business users)
- Fast analytical query performance 
- Join with Dimensional Table only (Good for OLAP not OLTP)

#### 3NF Data Model
#### Disadvantages

- Lots of expensive joins 
- Hard to explain to business users


## Database Summary :

Used the DVD rental database and PostgreSQL as a RDBMS.

Here is the 3NF Database Schema. [Here](https://github.com/Manav-56/Data-Warehouse-using-PostgreSQL/blob/main/3NF%20.png)

The DVD rental database represents the business processes of a DVD rental store. The DVD rental database has many objects, including:

- 15 tables
- 1 trigger
- 7 views
- 8 functions
- 1 domain
- 13 sequences

## Star Schema :

Build small Data Warehouse in PostgreSQL RDBMS. Convert 3NF Data Model into the Star Schema. [Here](https://github.com/Manav-56/Data-Warehouse-using-PostgreSQL/blob/main/start_schema.png)



## Steps:
 - Load Data into RDBMS
 - Understand database Schema
 - Spot candidates for Fact and Dimension Tables
 - Convert database Schema into Star Schema in this case




