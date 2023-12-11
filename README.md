## Introduction
Hello! It's my pet-project for upgrading and demonstrating my skills.

The essence of the project is to calculate the cost of storing goods from online marketplaces (in this case Ozon) and to visualize some analytics
That's why project was created: This online marketplace provides rather inconvenient reports for calculating the amount of storage of goods, so to simplify it, it was decided to create a similar solution that would be convenient for the company and correlate the values in the final table, as well as save all the results to the database.
P.S. first of all, the project was created to demonstrate the skills currently available

Name|Description| Stack
-----------|:-------:|:--------: 
Storage costs| Data on storage and coefficients for this have been uploaded. The cost of storage was calculated, some analytics were carried out, supported by visualization. | Numpy, pandas, seaborn, matplotlib, datetime, warnings, sqlite

## Requirements

Basic development tools:

* programming language Python3  and its libraries::

    + analytical library [Pandas](https://pandas.pydata.org/);

    + libraries for performing scientific and engineering calculations [NumPy](https://numpy.org/), [math](https://docs.python.org/3/library/math.html), [SciPy](https://scipy.org/);

    + libraries for data visualization [Matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/), [plotly](https://plotly.com/python/);

    + auxiliary libraries [datetime](https://docs.python.org/3/library/datetime.html), [display](https://ipython.org/ipython-doc/3/api/generated/IPython.display.html), [warnings](https://docs.python.org/3/library/warnings.html), [requests](https://pythonru.com/biblioteki/kratkoe-rukovodstvo-po-biblioteke-python-requests);

* programming environment [Jupyter Notebook](https://jupyter.org/);

* a language for working with databases (SQL).


## Main part of project
* Input: data on the quantity of stored goods (used/remains) and storage coefficients in each city (used/coeff)   (in repository data for an example) <br>
* Next, calculate the storage costs for each day for each product in each city, creating a summary table for the week <br>
* Output: get graphs with which to see storage costs, xlsx files for each day and week, a database that stores data for each week  (in repository data for an example) <br>
![data about coef](https://github.com/KirillKlem/storage_costs/assets/57907908/3fcd79c9-0706-4e50-aec4-cf49621d4e5b)
![data about remains](https://github.com/KirillKlem/storage_costs/assets/57907908/246e5e53-0205-4036-8591-72cd64611161)
![pivot table for week](https://github.com/KirillKlem/storage_costs/assets/57907908/9763e177-9d8c-478e-95da-e83a598e4b02)
![graph for amount of storage in city](https://github.com/KirillKlem/storage_costs/assets/57907908/bfc8bed0-3668-4b21-b86c-38c11e7c1895)
![graph based on dependence of cost of storage on factor](https://github.com/KirillKlem/storage_costs/assets/57907908/48374ba5-9f16-442f-a7a5-058015be9321)





