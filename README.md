# kickstarter_project


Kickstarter is one of the biggest crowdfunding platforms in the world and allows people from all over the globe to back new inventions and creative projects that capture their interest, ranging from Arts/Comics to Tech Design and Music. Since its launch in 2009, the crowdfunding platform has raised over USD 4.6 billion and continues to raise over USD 1.5 million a day. It operates on an all-or-nothing model, and funds are only released if a campaign meets its funding goal by the deadline. The dataset used in this project was obtained from webrobots.io, an online webscraper service. It includes all Kickstarter campaigns from March 2016 to July 2020. The aim of this project is to identify the common characteristics of successful projects and thus increase the likelihood of a future project succeeding, and to train a machine learning model that is able to accurately predict whether or not a campaign was successful. This project was inspired by Laura Lewis' submission on Medium (https://towardsdatascience.com/using-machine-learning-to-predict-kickstarter-success-e371ab56a743).

To increase the chances of campaign success, project creators are recommended to:

launch projects in music, specifically Rock and Country music and in Books

launch projects in the month of March

launch projects on Tuesdays

increase marketing activity between 2pm to 6pm as there is higher donation activity during these times

set a lower goal amount (around 3500 USD)

set a campaign length of around 30 days

aim to have the project picked by staff


Things to avoid include:

launching projects in Web, Mobile Games, Software and Restaurants

launching projects at the end of the year (October, November, December)

lauching projects on the weekends

launching projects between 8pm to 12pm

setting a high goal amount

having a campaign length longer than a month

The machine learning model used to predict whether or not a project would be successful was trained using Logistic Regression, Random Forest and XGBoosting. All three models performed well. The accuracy scores are as follows:

Logistic Regression 78.15%

Random Forest 89.49%

XGBoosting 90.19%
