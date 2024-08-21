<a name="readme-top"></a>

  <h1 align="center"><a href="https://github.com/HaniffZaid/KoNoHa-Property.git">
    <img src="KONOHAgold.png" alt="Logo" width="400" height="264">
  </a>

  HOUSE PRICE PREDICTION IN KUALA LUMPUR</h1>
   <h2><p align="center">
     Produced by KONOHA HOLDINGS
   <p align="center">[ Kamilla Halil, Nasharuddin Ghazali & Haniff Zaid ]</p>
   </p></h2>

  <!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#background-of-the-project">Background of the Project</a></li>
    <li><a href="#team-structure">Team Structure</a></li>
    <li><a href="#problem-statement--objectives">Problem Statement & Objectives</a></li>
    <li><a href="#flowchart">Flowchart</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgement">Acknowledgement</a></li>
  </ol>
</details>


<!-- Background of The Projects -->
## Background of The Project

KONOHA Holdings has been tasked to produce a house price prediction model within a week. After some quick research, we decided to focus on datasets available in Federal Territory of Kuala Lumpur. House price prediction model are expected to HELP BUYERS i.e. people who plan to buy a house so they can know the price range in the future, then they can plan their finance well. In addition, house price predictions are also beneficial for HELP SELLER i.e. property investors to know the trend of housing prices in a certain location.

### Methodology

We divide the SOPs into four phases which are:

| Phase 1: PLANNING | Phase 2: DATA PREPARATION | Phase 3: ML MODELLING | Phase 4: DEPLOYMENT |
| ------------- | ------------- | ------------- | ------------- |
| 1.Define goals | 5. Get data | 9. Create model | 13. Present Model |
| 2. Organize resources | 6. Clean data | 10. Validate model | 14. Deploy model |
| 3. Coordinate team | 7. Explore data | 11. Evaluate model | 15. Modify model |
| 4. Schedule project | 8. Refine data | 12. Refine model | 16. Model maintenance |


### Project Location

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              101.61866004946938,
              3.2256216237932307
            ],
            [
              101.61866004946938,
              3.101070592555459
            ],
            [
              101.78437953118771,
              3.101070592555459
            ],
            [
              101.78437953118771,
              3.2256216237932307
            ],
            [
              101.61866004946938,
              3.2256216237932307
            ]
          ]
        ],
        "type": "Polygon"
      }
    }
  ]
}
```
<p align="center">Federal Territory of Kuala Lumpur</p>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Team Structure -->
## Team Structure

```mermaid
graph TD;
    A(KAMILLA HALIL : Team Leader)-->B(HANIFF ZAID : Data Engineer);
    A(KAMILLA HALIL : Team Leader)-->C(NASHARUDDIN GHAZALI : ML Engineer);
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Problem Statement & Objectives -->
## Problem Statement & Objectives

In a house price prediction model project, the common problem statements typically revolve around understanding and predicting the value of residential properties based on various features. Here are some common problem statements you might encounter:

1. **Predicting House Prices**:
   - *Problem Statement:* "Given a dataset with various features of houses (such as size, location, number of bedrooms, etc.), predict the selling price of a house."
   - *Objective:* Develop a predictive model that accurately estimates house prices based on input features.

2. **Feature Importance Analysis**:
   - *Problem Statement:* "Determine which features (e.g., number of bedrooms, location, square footage) are the most influential in predicting house prices."
   - *Objective:* Identify and rank the importance of different features to understand what drives house prices.

3. **Price Estimation for Different Locations**:
   - *Problem Statement:* "Estimate house prices for properties in different geographical areas, taking into account varying market conditions and local characteristics."
   - *Objective:* Create a model that can account for regional differences in housing prices and provide accurate estimates for various locations.

4. **Handling Missing Data**:
   - *Problem Statement:* "Address and handle missing or incomplete data in the housing dataset to improve the accuracy of the price prediction model."
   - *Objective:* Implement strategies to manage missing values and ensure that the model can still make reliable predictions.

5. **Model Comparison**:
   - *Problem Statement:* "Compare the performance of different regression algorithms (e.g., linear regression, decision trees, random forests) in predicting house prices."
   - *Objective:* Evaluate and compare the effectiveness of various machine learning models to identify the best-performing approach for price prediction.

6. **Addressing Outliers**:
   - *Problem Statement:* "Identify and manage outliers in the housing dataset that may distort the predictions of house prices."
   - *Objective:* Develop methods to detect and handle outliers to improve the accuracy and robustness of the predictive model.

7. **Time Series Analysis for Price Trends**:
   - *Problem Statement:* "Analyze and predict trends in house prices over time, considering historical data to forecast future price movements."
   - *Objective:* Build a time series model to understand and predict how house prices change over time.

8. **Impact of Economic Factors**:
   - *Problem Statement:* "Assess the impact of economic factors (e.g., interest rates, unemployment rates) on house prices and incorporate these factors into the predictive model."
   - *Objective:* Integrate macroeconomic indicators into the model to enhance price predictions and account for broader economic influences.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FLOWCHART -->
## Flowchart

```mermaid
graph TD;
    A(Data Collection & Data Scraping:Haniff)-->B(Data Cleaning & Data Preprocessing);
    B-->C(Flow A:Nash);
    B-->D(Flow B:Kamilla);
    C-->E(Exploratory Data Analysis)
    E-->F(Training Model)
    F-->G(Model Performance Evaluation)
    G-->H(Data Testing)
    D-->J(Exploratory Data Analysis)
    J-->K(Training Model)
    K-->L(Model Performance Evaluation)
    L-->M(Data Testing)
    H-->I(Presentation)
    M-->I
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Kamilla Halil - [Github](https://github.com/kameerahariru)

Muhd Nasharuddin Bin Ghazali - [Github](https://github.com/Nash887)

Mohd Haniff Bin Zaid - [LinkedIn](https://www.linkedin.com/in/HaniffZaid) - [Github](https://github.com/HaniffZaid) - [Gmail](mailto:anipzaid@gmail.com)

Project Link: [Github](https://github.com/kameerahariru/KoNoHa-Property.git)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGEMENT -->
## Acknowledgement

We want to express our appreciation to our Data Science Bootcamp trainer, Dr. Fairoza Amira Binti Hamzah, for all the knowledges you have given us from the start till the end of the bootcamp. We hope to gain much more knowledge by joining your team in the future. May Allah bless you with success, health, happiness, patience and strength.

Dr. Fairoza Amira - [Github](https://github.com/FairozaAmira) - fairozaamira@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>
