# Investment Options Evaluation
For this assigned we need to evaluate four new investment options for inclusion in the a client's portfolio. We’ll need to determine the fund(s) of the four listed in the data csv in the Resources Folder. We are utilizing key risk-management metrics: 
> 1. Daily rReturns 
> 2. Standard deviations
> 3. Sharpe ratios
> 4. Variance
> 5. CoVariance
> 6. Betas
> 
---


## Installation

Activate Conda Dev environment make sure to install the following packages
if you do not have them already:

* pandas
* numpy
* pathlib
* os
* matplotlib (pyplot)

While you could use the package manager [pip](https://pip.pypa.io/en/stable/) to install these individually please make use of the requirement text in the repo.

```bash
python -m pip install -r requirements.txt
```

## ABOUT THE CODE
There isnt much to talk about here:

### 1st thing FUNCTIONS
I created two functions.  I will continue to iterate on these functions but I want a function that will take data from either an api or a csv (maybe even a database and parse filter and clean it according to the data type. Right now we are working with  stock prices and a datetime index. As we work with other data types Ill build and add to this. The second function  takes as an argument a dataframe and returns information about it. I tend to use this while I am developing so I know at all times what I am working with.

### First Function
<img width="1079" alt="Screen Shot 2022-04-17 at 10 46 52 PM" src="https://user-images.githubusercontent.com/101449950/163746479-1ce30563-8cdb-461e-ae85-65d133417182.png">


### Second Function
<img width="687" alt="Screen Shot 2022-04-17 at 10 52 36 PM" src="https://user-images.githubusercontent.com/101449950/163746961-eceef013-e60d-47bf-b7b3-e49f7577e247.png">

### Future Directions: 
We would also need a function that will take care of all the plotting because  as well. it is an opportunity to increase efficiency.


### PLotting
One issue I had with this assignment is that not much thought is given to the. readibility of graphs. I believe this was done in part because  we are left to comntnue studying on our own and the documentation  for plotting using mathplotlib or seaborn is quite vast. I believe that there are more opportunities to future drive home many interesting insights from the course material.

#### For example

<img width="518" alt="Screen Shot 2022-04-17 at 10 59 39 PM" src="https://user-images.githubusercontent.com/101449950/163747714-d9e8be3d-d969-4c70-b648-f7dceffb91b2.png">

I decided to compare two things the graph for the rolling Betas for BRKA adn TIGR with the graph of their average 60-day rolling beta. The visuals are interesting and help better differentiate between what is happening programmatically. You can can how the curves are smoothed out but the insights are still there.

<img width="927" alt="Screen Shot 2022-04-17 at 11 05 24 PM" src="https://user-images.githubusercontent.com/101449950/163748131-dac28857-933a-40cb-988f-389dd89ac21e.png">
