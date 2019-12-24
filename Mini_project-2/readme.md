
# DATA



### In the AidData dataset, each row represents a financial transaction between two countries. The dataset contains the following attributes:
1. Year: year of the commitment
2. Donor: country providing the financial resource
3. Recipient: country or organization receiving the money
4. Commitment Amount: the total amount of financial resources provided
5. Coalesced Purpose Name: the purpose of the transaction


Link to data - https://www.aiddata.org/data/aiddata-core-research-release-level-1-3-1

Note - have used reduced version of this dataset

# GOAL

## Create visualizations to answer the following questions :

**Visualization 1:** 

1.  How does the amount donated vs. amount received change over time across all countries?; 
2.  Are there countries that mostly send or mostly receive and countries that have a similar amount of donations they receive and send?; 
3.  Are there countries that change their role over time? That is, they used to mostly send donations and turn into mostly receiving donations and vice-versa?; 
4.  Are there countries in which you can find a sudden increase ("peak") or a sudden decrease ("valley")?

**Visualization 2:** 

Focusing on the Coalesced Purpose of the donations, focus on the top 10 donations purposes. What are the top 10 purposes of disbursements (in terms of total amount of disbursement) and how does their relative amount compare over time? E.g., are there purposes that tend to be prominent for a period of time and others that become more prominent during other periods? Hint: looking at the graph one should be able to say something like: “Ah! During these years donations were mostly about X but then there were way more donations about Y”.



# Method

1. Preprocessing data in python using pandas and numpy
2. Using preprocessed data to create visulaizations in D3

#### Reason behind Visualizations and observations are in" Visualization_description.pdf"

# Visualization 1:

<img src="D3 Visualization/Que-1.png">

# Visualization 2:

<img src="D3 Visualization/Que-2.png">


```python

```
