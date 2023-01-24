# discover-data-eng-workshop

The purpose of this repo is to make you discover the profession of "data engineering" differently.

Through a fictitious use case, we will build a data pipeline that will introduce us to the profession of data engineer and the tools or technologies necessary for this profession.

## - Begining question

What do you know about data engineering Role ?


## Data creates value for business !

A few business question  that we could want to answer each days with data 

1 - What is the average loan amount for grade of loan A, B, C, D ?
2 - How does the loan amount vary by home ownership status?
3 - What is the average annual income for each income category?
4 - What is the average interest rate for each loan purpose?
5 - How does the loan term vary by region?
6 - What is the total amount of payments made on loans for each grade?
7 - How does the loan condition vary by application type?
8 - What is the average debt-to-income ratio for each grade of loan?
9 - How does the annual income vary by home ownership status?
10 - What is the total recovery amount for loans in each grade?



## Definitions

- In Airflow, a DAG – or a Directed Acyclic Graph – is a collection of all the tasks you want to run, organized in a way that reflects their relationships and dependencies. A DAG is defined in a Python script, which represents the DAGs structure (tasks and their dependencies) as code.

- Operators are the building blocks of Airflow DAGs. They contain the logic of how data is processed in a pipeline. Each task in a DAG is defined by instantiating an operator. There are many different types of operators available in Airflow.

- In Airflow, XComs (short for "cross-communications") are a mechanism that lets tasks talk to exchange data between themselves. An XCom is identified by a key (essentially its name), as well as the task_id and dag_id it came from.

- Hooks are interfaces to services external to the Airflow Cluster. While Operators provide a way to create tasks that may or may not communicate with some external service, hooks provide a uniform interface to access external services like S3, MySQL, Hive, Qubole, etc.



## Ending Question
 Which kind of technologies do you think a Data Engineer needs for his job basing on what we saw together ?

