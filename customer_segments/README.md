# Content: Unsupervised Learning
## Project: Creating Customer Segments



### Code

In this project, I analyzed a dataset containing data on various customers' annual spending amounts (reported in monetary units) of diverse product categories for internal structure. The goal of this project is to best describe the variation in the different types of customers that a wholesale distributor interacts with. Doing so would equip potential distributor with insight into how to best structure their delivery service to meet the needs of each customer.


Template code is provided in the `customer_segments.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `customers.csv` dataset file to complete your work.  Note that the code included in `visuals.py` is meant to be used out-of-the-box for visualisation.

### Run

In a terminal or command window, navigate to the top-level project directory `customer_segments/` (that contains this README) and run one of the following commands:

```bash
ipython notebook customer_segments.ipynb
```  
or
```bash
jupyter notebook customer_segments.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Note (m.u.) is shorthand for *monetary units*.

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous);
2) `Milk`: annual spending (m.u.) on milk products (Continuous);
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous);
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous);
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal)
