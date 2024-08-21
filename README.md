# CSCA 5622 Supervised Learning Final Project - Telecom Churn Prediction


# Problem Statement

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business
goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, we try to analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.

The goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage. This is a classification problem.

## Dataset
For this project I am using a public data set from a Kaggle Hackaton.Below is the link to the data:

Citation \
Tannu Jain, Tejaswini Ravinder, Upgrad. (2022). Telecom Churn Case Study Hackathon. Kaggle. \
https://kaggle.com/competitions/telecom-churn-case-study-hackathon-c42

### Description
**Files**
- train.csv - the training set
- test.csv - the test set
- data_dictionary.csv - supplemental information about the data

**Columns**
- example_id - definition of example_id
- feature_1 - definition of feature_1
etc.

**Data_Dictionary**
| Acronyms | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| CIRCLE_ID | Telecom circle area to which the customer belongs to                        |
| LOC      | Local calls within the same telecom circle                                  |
| STD      | STD calls outside the calling circle                                        |
| IC       | Incoming calls                                                              |
| OG       | Outgoing calls                                                              |
| T2T      | Operator T to T i.e., within the same operator mobile to mobile             |
| T2M      | Operator T to other operator mobile                                         |
| T2O      | Operator T to other operator fixed line                                     |
| T2F      | Operator T to fixed lines of T                                              |
| T2C      | Operator T to its own call center                                           |
| ARPU     | Average revenue per user                                                    |
| MOU      | Minutes of usage for voice calls                                            |
| AON      | Age on network; number of days the customer is using the operator T network |
| ONNET    | All kinds of calls within the same operator network                         |
| OFFNET   | All kinds of calls outside the operator T network                           |
| ROAM     | Indicates that the customer is in a roaming zone during the call            |
| SPL      | Special calls                                                               |
| ISD      | ISD calls                                                                   |
| RECH     | Recharge                                                                    |
| NUM      | Number                                                                      |
| AMT      | Amount in local currency                                                    |
| MAX      | Maximum                                                                     |
| DATA     | Mobile internet                                                             |
| 3G       | 3G network                                                                  |
| AV       | Average                                                                     |
| VOL      | Mobile internet usage volume in MB                                          |
| 2G       | 2G network                                                                  |
| PCK      | Prepaid service schemes called PACKS                                        |
| NIGHT    | Scheme to use during specific night hours only                              |
| MONTHLY  | Service schemes with validity equivalent to a month                         |
| SACHET   | Service schemes with validity smaller than a month                          |
| *.6      | KPI for the month of June                                                   |
| *.7      | KPI for the month of July                                                   |
| *.8      | KPI for the month of August                                                 |
| FB_USER  | Service scheme to avail services of Facebook and similar social networking sites |
| VBC      | Volume-based cost when no specific scheme is purchased and paid as per usage |

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - imbalanced-learn
  - XGBoost

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/himanshudongre/telecom-churn-prediction.git
2. Navigate to the project directory:
   ```bash
   cd telecom-churn-prediction
3. Install the required packages
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/telecom-churn-prediction.ipynb
5. Run the cells in the notebook to execute the data analysis and model building steps.
   
