Hi!

This project aims to explain the basics of accessing and modyfing account specific Snowflake ressources inside a Python environment, in this case using a Jupyter Notebook and Anaconda.
The code is designed to help the general public or my clients to get started with Snowflake using Python instead of the browser interface :)


The following libraries are needed: 

- os (to access the key/value pairs inside the env. file)
- load_dotenv from dotenv (to load the env. file in which sensible account access information are saved into the notebook)
- snowflake-connector (to build a connection to Snowflake and run SQL commands)
- pandas (for DataFrames etc.)
