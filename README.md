# Random python app test
Calculate fertile land area in square meters, sorted from smallest area to greatest and separated by a 
space, given submitted coordinates of barren land.
## Preparation
Install [Python](https://www.python.org/)  
Pull down the repo.  
Open a mac terminal window or windows command prompt.  
Before running tests or the application, navigate to the root of the BarrenLandAnalysis folder.  
## Running the unit tests 
The following command will execute all of the tests.
```
py -m unittest discover -v
```
## Running the application
```
py run.py
```
At the prompt, enter barren sections. For example,
````
{"0 292 399 307"}
or
{"48 192 351 207", "48 392 351 407", "120 52 135 547", "260 52 275 547"}
