Within this folder are the files for the Undergraduate 4810 AI Final Project for Janou Milligan and Zachary Kennedy.
This folder consists of (from top to bottom):
     -The final paper in IEEE format
     -The final powerpoint
     -The jupyter notebook holding the code for the project
     -The anaconda environment holding all the packages used within jupyter
     -This README

Regarding the Jyputer notebook, it uses imports from standard libraries for most AI and machine learning development projects such as
     -pandas 
     -numpy 
     -tensorflow
     -sklearn
     -matplotlib
     -keras
     -seaborn 

along with additional imports specific to our project such as
     -pycaret
     -scikeras
     -torch
     -xgboost
     -plotly

All packages for these libraries are contained within the "Final_Project_env.yaml" file and are ready to be imported into anaconda. However, if you are not using an anaconda environment to run Jupyter, you may have to install these packages manually if you intend to run the code. Thus, the end of this file will contain links to the library documentions which will detail how to go about doing that.

Some additional notes for the code:
I left all the outputs visible to show that the code has been ran through fully. If you want to clear these these you can right click anywhere on the notebook and hit "Clear all outputs"
Running the code is fairly simple if you are already familiar with Jupyter notebooks, if not then you can simply select each cell and hit shift+enter to run it. I reference cells by the numbers that are displayed to the left of each cell in a "[#]:" format
When instantiating the models, this will take some time (roughly 5 minutes at most for cells [48], [49], [50], and [51]. Cell [56] stacks are the previously selected models and takes around [15] minutes to run. These times are based on my experience running the code on my computer.
Cell [58] will load a comprehensive evaluation of the final model where you can generate differing plots and charts. I wanted to include more into the final paper but there's a lot to cover for each chart.

That is all from me, I hope you enjoy the code and thanks for a fruitful semester
-Janou Milligan


Links to library documentations:
pycaret: https://pycaret.gitbook.io/docs/get-started/installation
torch: https://pytorch.org/
xgboost: https://xgboost.readthedocs.io/en/stable/install.html
plotly: https://plotly.com/python/getting-started/#installation