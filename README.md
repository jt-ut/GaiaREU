# Machine Learning Workshop for UT Astronomy's REU Program!

To run in Google Colab, view the preview of GaiaREU-ML_v2024.ipynb and click the "Open in Colab" link at the top (make sure you are signed in to a Google account). 


Alternatively, to run locally, follow these setup instructions: 
1. Download the GaiaREU-ML_v2024.ipynb notebook from github

2. From your local computer, open a terminal and issue the following commands, one per line:
```
python -m venv REUMLENV
source REUMLENV/bin/activate
pip install pandas numpy matplotlib seaborn scikit-learn yellowbrick jupyter
REUMLENV/bin/jupyter notebook
```
The first line creates a virtual Python environment that we will work from, as not to disturb your local Python environment. 
The second line activates this environment for use. 
The third line install the packages necessary for today's workshop. 

3. From the Jupyter environment just created, open the notebook you downloaded in step 1, and switch the kernel to "REUMLENV"

4. When we are finished, you may close Jupyter like normal, and type the following in the terminal window to close your virtual Python environment:
```
deactivate
```
   

