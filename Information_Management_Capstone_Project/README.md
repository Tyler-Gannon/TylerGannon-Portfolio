These two files contain two of the code files used for a data pipelining / transformation capstone project in the Information Management course at the University of Texas at Austin MSBA program.

The SQL code was used to create and store tables in Snowflake - containing a silver layer for preliminary transformation of the data, and a gold layer for more polished tables ready to be used by top end business users.

The .pynb file contains python code in a Snowpark session in Jupyter notebook that runs two analytical models to determine 'long term credit-card accounts' and which products cost the most for the company to ship. The long term credit-card account holders data was pushed back to Snowflake as a table in the gold layer of the medallian architecture.
