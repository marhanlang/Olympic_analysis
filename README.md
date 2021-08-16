# Olympic_analysis
Communication Protcol: Slack & Zoom

Predicting medal placement in the Olympics based on BMI in the Summer and Winter Olympics

Reason for Topic: Upcoming Summer Olympics in Tokyo

Data: 120 years of Olympic Results

Data on athletes and medal results from Athens 1896 to Rio 2016 from Kaggle

Question: Can we predict Olympic winners based on BMI in the Summer and Winter Olympics?

Data Exploration: Cleaned data in Jupyter Notebook and Excel, Calculated Data in Excel, Created Database in PGAdmin

Data Analysis: LabelEncode Medal column, Drop unneccessary columns, Features include Age, Height, Weight and BMI, Target is the Medal column

The size of our dataset led us to choose a neural network model. The neural network model generally has higher accuracy even with data that has a lot of noise. The hidden layers aid in finding relationships despite noise. This is an advantage when handling large datasets. We have included 2 hidden layers within our model: a relu layer with 8 nodes first and a tanh layer with 5 nodes. Throughout 100 epochs, we observed in increase in loss while accuracy remained stable.

Presentation: https://docs.google.com/presentation/d/1H-2fYo0RwPQaH8hvshB_OXYWtTTLEvcz3QlgXFZ8zSM/edit?usp=sharing

Data: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results

Dashboard: https://marhanlang.github.io/Olympic_analysis/
