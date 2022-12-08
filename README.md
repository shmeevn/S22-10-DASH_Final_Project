# S22-10-DASH_Final_Project
This repo contains the finalized S22-10-DASH project files for predicting solar panel output using Keras LSTM.

# Usage Information
Using CMD, PowerShell or any other terminal capable of running Python code, use the commands below:
```
python testbench.py save weather
```
This will start the program, train a new model using the parameters specified in the testbench, and save the trained model in the programs directory.
```
python testbench.py load weather
```
This will start the program, load a previous trained model, and start the main program loop which generates figures constantly.

You can also load or save the noweather model using the same method. This will just ignore all weather parameters and use only time and historical PV data.

The output of the program can be viewed by opening the figpage.html file in a browser while the program is running in load mode.

# Screenshot
![image](https://user-images.githubusercontent.com/100383906/206312543-f6ed66a6-4b55-4e16-8eb2-a030faf1e0f6.png)

# Requirements
Several dependencies are required to run this code. They can be installed using the following command template:
```
pip install keras
```
The list of dependencies to be installed are as follows:
```
keras
pandas
numpy
sklearn
matplotlib
datetime
```
Linux OS installations will already have the ability to run Python code, but for Windows OS installations, you will need to install Python for the command line. This can be found on the Microsoft Store for free.
