# SimpFileConv
We come across many types of readable file formats. Sometimes there is a need of viewing the same data in a different file format. For example, we have some data stored in a CSV format but it might be inconvenient for a machine to comprehend it easily. So we need to convert the same CSV to a machine readable language like JSON etc. in such a way that no data is modified during the process.

In this minor project, CSV to JSON conversion is offered alongside an easily understandable Graphical User Interface.

Basic Requirements:-

python >= 3.5

CSV and JSON libraries

pandas

tkinter

time modules


Follow these steps:
```bash
git clone https://github.com/PradHolla/SimpFileConv.git
```
Now, open the folder
```bash
cd SimpFileConv
```
# Primary Implementation
Run the Python File

```bash
python primary.py
```
If you are a Linux user with python3, enter the below command
```bash
python3 primary.py
```
Now the program asks for the location of the required CSV File

```bash
Sample.csv
```
Note: Manual location of the CSV file present in the system can also be given.

The converted JSON format is displayed in the console with the total time taken for conversion.
# Secondary Implementation
This is another implementation where user can convert using a GUI. This is a demonstration of large scale implementation of file conversions.

Installation

The necessary libraries\modules to be installed are specified in requirements.txt. Run the below command to install them
```bash
pip install -r requirements.txt
```
Run

Executing the below command launches a GUI
```bash
python secondary.py
```
For Linux users:
```bash
sudo apt-get install python3-tk
```
Then
```bash
python3 secondary.py
```
Import a CSV file from your system by using 'Import CSV'.

Then select Convert 'CSV to JSON' and give a name to the output file in the desired location.

The converted file will be present in the pre-specified directory.
