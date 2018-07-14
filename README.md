# Spark Exercise
Spark "exercise" on page view data

## Running the script

### Prerequisite
- Python2.7
- Spark (of course!)
- Jupyter
- Hadoop (optional if you are getting data from AWS s3)

### Page view data
In this project data are previously downloaded and imported locally, for simplicity sake. 

One may also setup the AWS access and getting the data from AWS s3. But remember to update the script manually.

### Suggested Installation

#### 1. Use virtualenv
1. Ensure python2.7, virtualenv are locally installed
2. `$ virtualenv --python=python2 venv`
3. `$ source venv/bin/activate`
4. `$ pip install pyspark jupter`

#### 2. Use spark directly
1. Ensure python2.7, spark are locally installed
2. `$ pip2 install jupyter`
3. Setup env (you can also paste into `~/.bashrc` or `~/.zshrc`)
    ```bash
    $ export PYSPARK_DRIVER_PYTHON=jupyter
    $ export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
    ```

## Remarks
- In this repo data are assumed download, 
- `3. Basic View Analysis` is refering to question 1; `4. Session Analysis` is refering to question 2
- Assumed data with empty article_id / user_id are invalid and hence removed (?)
- For question 1d. Assumed average/ median pageview per user is meant to be **a single value** instead of a list of value per user
- For question 1d. Median are calculated as an approximate value for simplicty.