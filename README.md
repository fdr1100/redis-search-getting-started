# redis-search-getting-started
Get Started with Redis Search 

Searching is a key need in any enterprise, and in this age of real-time data, it is crucial that search engines be as fast and effective as possible.
As more and more data is used by application front-ends serving the end user, the need for fast processing of that data keeps increasing. The good news is that much of the analytics and search needs can be done thru an in-memory database serving the front-end.

The Jupyter Lab/Notebook attached allows you to get started with Redis Search. All you need is access to a Redis Enterprise database.

Steps:

1- Create a Redis Enterprise Database with Redis Search and Redis JSON modules.

1.1. You can create a free account and database following this link:
https://docs.redis.com/latest/rc/rc-quickstart/

1.2 Update the database credentials (endpoint, port and password) in the Jupyter Lab/Notebook

2 - Run the Jupyter Lab/Notebook

2.1 Create a python virtual environment with Python 3 and jupyter options and load the requirements. For example:

> conda create -n redis-search python=3 jupyter

2.2 Copy the notebook file and the requirements.txt to the current folder

2.3 Activate the virtual environment and install requirements.

> conda activate redis-search

 (redis-search) <your system path> % pip install -r requirements.txt

2.4 Run Jupyter Lab or Jupyter Notebook

 (redis-search) <your system path> % jupyter lab 
