# Kickstarter Project Success Predictions

## Abstract
As one of the leading crowdfunding platforms, Kickstarter brings creative projects to life. Creators come forward with innovative ideas and backers fund their developement. Given a deadline, if the creator receives full funding for their idea, they are able to 'kickstart' their project. However, given millions of ideas, can we predict if a kickstarter will succeed at project launch? 

Our goal is to develop a machine learning model that can accurately predict if a kickstarter will succeed. This can help two audiences: the creators and the backers. Creators can use the model as a preliminary baseline to see if their proposed idea might succeed and tune their proposal to maximize success. Backers can use the model as a basis when deciding to "back" the creator ot not.

## Data Source
We are provided with 2 CSVs sourcing from https://www.kaggle.com/datasets/sripaadsrinivasan/kickstarter-campaigns-dataset.
This dataset contains data about failed, canceled, and successful kickstarter campaigns. For example, we analyze the timing of campaign posts, types of projects, and locations of campiagn and their descriptions.

## Model Guide

Modeled contexts are located in /src/models.

- **"...with_other_leakage.ipynb"** The spotlight feature is removed but all other forms of leakage features remain.
- **"...with_spotlight_leakage.ipynb** The spotlight leakage feature is present.
- **"...feature_rank.ipynb** A stable decision tree modeling context with feature ranking and additional graphs.
- **"...inconclusive_kickstarters_eliminated.ipynb"** Possibly eliminates another form of bias in the original dataset. Omits inconclusive kickstarters marked as failures for reasons of cancellation, suspension, or pending.
- **"classification_tree.ipynb"** A stable decision tree modeling context without feature ranking or additional graphs.

## Team Members
- Harini Anand
- William Green
- Zarah Taufique

