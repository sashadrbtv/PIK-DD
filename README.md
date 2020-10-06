# PIK Digital Day 14.07.2018

One of the unsolved problems in the **construction industry** is a fairly accurate prediction of sales depending on the price and hundreds of other parameters. Unlike the classic tasks of forecasting sales of the same goods, each apartment is a unique product with a unique price, which creates a number of methodological challenges at once.

The first stage of this championship was online. It was necessary to develop a forecasting model of sales for three months ahead in the context of buildings and apartments of a certain room number in different projects and get into the top 80 places. The second stage was a 1-day hackathon (offline). 

As a training dataset, the history of apartment sales in 2.5 years was provided for 30 projects in Moscow and the Moscow Region. It contains information about the parameters of apartments, transport accessibility, sales history, history of status changes, and external economic parameters. The evaluation metric is **RMSE**.

The repo consists of an **IPython notebook** with Data Preprocessing techniques and Linear Regression modeling process (**it's only a part of final solution**). And also a **final presentation** of the team, which took place at Yandex 28.07.2018 (a video link: https://youtu.be/qSehSTWMXaY?t=4213 and an article: https://goo.gl/2dfwGB)

**The results**: **the 1st place** for Linear Regression solution and **the 2nd place** for the model w/o restrictions (a blend of 80% XGB model and 20% Linear Regression) 
