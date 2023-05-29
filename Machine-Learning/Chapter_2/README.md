# End-to-End machine Learning Project
In this chapter you will work through an example project end to end ,pretending to be a recently hired data scienctist at a real estate company .Here are the main steps you will go through :
<li>Look at the big picture </li>
<li>Get thee data </li>
<li>Discover and visualize the data to gain insights</li>
<li>Prepare the data for Machine Learning algorithms </li>
<li>Select the data for Machine Learning algorithms </li>
<li>Select a model and train it </li>
<li>Fine tune your model </li>
<li>present your solution</li>
<li>Launch ,monitor ,and maintain your system</li>
# Look at the Big Picture 
Welcome to the ML Housing Coporation ! your first task is to use california census data to build a model of housing prices in the state .your model should learn from this data and able to predict the median housing price in any district ,given all the other metrics .
# Frame the problem :
the first question to ask your boss is what exactly the business objective is building a model is probably not the end goal .How does the company expect to use and benefit from this model ?knowing the objective is importna t because it will determine how you frame the problem ,which algorithms you will select ,which performance measure you will use to evaluate your model ,and how much effort you will spend tweaking it .First,,you need to frame the problem :is it supervised ,unsupervised ,or Reinforcement Learning ?is it classification task, aregression task ,or something else ?shoud you sue batch learning or online learning techniques?
# Select a performance measure 
Your next step is to select a performance measure .A typical performance measure for regression problems is the Root Mean Square Error(RMSE).it gives an idea of how much error the system typically makes in its predictions with a higher weight for large error 

![mse_5](https://github.com/abdelrahman300/AI/assets/62572088/873f690e-1efb-4689-8c5d-75da78e025a0)

# Even though the RMSE is generally the preferred performance measure for regression tasks in some contexts you may prefer to use another function .for example ,suppose that there are many outlier districts .in this case ,you may consider using the mean absoulute error 

![download (20)](https://github.com/abdelrahman300/AI/assets/62572088/f17030ec-888c-42f4-bed0-6c182ec5a892)
