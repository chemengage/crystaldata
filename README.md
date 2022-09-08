# crystaldata
Data cleaning and analysis tool for high-temperature crystal growth run data

# Instructions
## Opening the notebook in Google Colab
1. Click on [ADC_tool_v1.ipynb](https://github.com/chemengage/crystaldata/blob/main/ADC_tool_v1.ipynb) to view the notebook then click [Open in Colab](https://colab.research.google.com/github/chemengage/crystaldata/blob/main/ADC_tool_v1.ipynb)
2. Alternatively, just click [here](https://colab.research.google.com/github/chemengage/crystaldata/blob/main/ADC_tool_v1.ipynb) to access Colab directly
3. Once you're in Colab, ensure you're signed into your preferred Google account

## Setting up the notebook
### Uploading growth run data
1. Click the file directory in the left bar and navigate to the root directory ![root directory](https://github.com/chemengage/crystaldata/blob/main/images/root%20directory.PNG)
2. Right-click and create a new folder named 'growth run data' in the root directory ![growth run data](https://github.com/chemengage/crystaldata/blob/main/images/growth%20run%20data.PNG)
3. Right-click on 'growth run data' and click 'Upload'
4. Upload all growth runs of interest in CSV format

## Running the notebook
### Option 1
In the upper bar click Runtime > Run all. This will run the entire notebook with the default parameters under Parameters > User Inputs. The parameters can be changed later in the arguments of the plotting functions.
### Option 2
Make changes to the User Inputs and run each cell up to Import Data. Then click Runtime > Run after

## Plotting functions
1. Click the Table of Contents in the left bar and navigate to the Plotting functions ![plotting functions](https://github.com/chemengage/crystaldata/blob/main/images/table%20of%20contents.PNG)
2. Each plotting function is set up as a function (def) with a cell below to run the function. The arguments of this cell (do not change the 'def' cell) may be changed to adjust the plot (e.g., change time window, start/end times, etc.) ![change](https://github.com/chemengage/crystaldata/blob/main/images/plotting%20functions.PNG)
