# Predictive maintenance
 Early warning system for possible failures of mass storage devices based on machine learning mechanisms.
 
 The script uses a RandomForest classifier, which based on the appropriate Self-Monitoring, Analysis and Reporting Technology (S.M.A.R.T.) parameters of the drive is able  to determine the possibility of failure. The prediction was tested mostly on data from HDDs for 3, 7 and 14 days before failure. The prediction accuracy is approximately 96.4%-100%. More information in docs.

# Requirements
- Python 3.6+
- Jupyter Notebook (https://jupyter.org/install)

# Running
Run `script.ipynb` in Jupyter Notebook

# Data
The data used to train the algorithm was provided by Backblaze company
(https://www.backblaze.com/b2/hard-drive-test-data.html)

# Documentation
 `docs` directory (only in Polish)
 
# Example (prediction result for 14 days)
<table>
       <img width="430px" height="325px" src="https://dl.dropboxusercontent.com/s/uqdedyv9c7ticud/table.png?dl=0">
</table>
<table>
       <img width="430px" height="56px" src="https://dl.dropboxusercontent.com/s/wjmhkbi0hupfy6d/accuracy.png?dl=0">
</table>
