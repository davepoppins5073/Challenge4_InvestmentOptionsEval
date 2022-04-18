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

## Usage
There isnt much to talk about here regarding usuage or tow provoide screen shots bit I wanted to bring up two things:
### 1st thing
We need a function that will pull in data from a csv or api and then clean, parse filter and format it to what we need. Doing this more than once is painful. 
We would also need a function that will take care of all the plotting because  as well. it is an opportunity to increase efficiency and most importantly:
> ..."
> 
<img width="650" alt="Screen Shot 2022-04-10 at 11 35 39 PM" src="https://user-images.githubusercontent.com/101449950/162663246-c53edea9-bc7a-4b77-9114-5cbd19b73a13.png">

### 2nd thing
<img width="964" alt="Screen Shot 2022-04-10 at 11 36 43 PM" src="https://user-images.githubusercontent.com/101449950/162663278-6f6bd6f5-7127-4cf2-8981-ac2537316fca.png">

When I set the regex=False I was able to avoid the future warning that results. I wanted to make note to myself in the future. I dont think anyone else will be using this repository.


