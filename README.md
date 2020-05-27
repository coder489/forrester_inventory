## Instalation

Create a new repository and enter its respository name, such as for

After creating the remote repo, use GitHub Desktop software or the command-line to download or "clone" it onto your computer. Choose a familiar download location like the Desktop.

Then navigate there from the command line (subsequent commands assume you are running them from the local repository's root directory):

```sh
cd ~/Desktop/robo-advisor
```

## Environment Setup

Create and activate a new Anaconda virtual environment:

```sh
conda create -n ametza-env python=3.7 # (first time only)
conda activate ametza-env
```
Create a "requirements.txt" file that holds packages for: 
openpyxl

Then from within the virtual environment, install the required packages specified in the "requirements.txt" file you created:

```sh
pip install -r requirements.txt
```

Then, from within the virtual environment, demonstrate your ability to run the Python script from the command-line:

```sh
python app/forrester_inventory.py
```