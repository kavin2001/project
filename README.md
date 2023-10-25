# Task 1
## Analyze a Large Dataset of Fraud in Financial Payment Services

Here is the background information on your task
You have been asked to analyze a recently acquired dataset of mobile money transactions from a financial services provider. Let’s go into a bit more detail about the dataset to set the stage before you get started.

The dataset has five types of transactions:

CASH-IN is any deposit.
CASH-OUT is any withdrawal.
DEBIT is a specific type of withdrawal in which the money is sent to the user’s bank account.
PAYMENT is the purchase of goods or services. 
TRANSFER involves moving money from one user’s account to another user’s account.
You will also see two fields related to fraud tagging. IsFlaggedFraud is fraud detected by their automation system while IsFraud is fraud that truly occurred.

Now you have sufficient context to analyze the dataset. Happy exploring!

# Exploratory Data Analysis

Install Python3 in case it is not installed on your machine. Type python or python3 in your terminal of choice. You should see the Python interpreter show up. Next, we will want environment isolation so this project can be separate from the rest of your machine. You can do one of the following:

```
- Install Anaconda / Miniconda. Once installed
    - conda create --name forageenv python=3.9
    - conda activate forageenv
- Use venv
    - python3 -m venv forageenv
    - source forageenv/bin/activate
- Use another tool you are comfortable with
    - use it as your normally would
```


Install the required Python modules.
```
pip3 install -r requirements.txt
```

Start the jupyter notebook
```
jupyter notebook
```
