# PROTEIN TRUNCATOR TOOL
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Tool that matches the mass spectrum peaks to the corresponding protein fragments

The link to the application:


The tool was written using Python and Jupyter notebook. Voila was used to convert the notebook to the standalone application. The app was hosted in mybinder.org

## How the app works
❃ The app asks the user to provide the sequence of the protein of interests and the mass corresponding to the peak that user wants to check. 
❃ User is also asked to provide the Difference, the mass interval from the mass corresponding to the peak. 

❃ The app generates all possible fragments that have the mass within the choosen range. For instance if the user provided the  mass corresponding to the peak = 18000 Da and the difference of 23 Da the tool will generate all fragments that have the mass in the interval 17977 (18000-23) to 18023 (18000+23) and sorts them by module of mass difference from the provided peak.

❃ The result is downloadable as xlsx (excel) file. First 50 fragments in the list are shown on the screen.

