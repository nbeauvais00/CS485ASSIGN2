# CS485ASSIGN2
ASSIGNMENT 2 CS 485
HW2: Chord Recognition
In this assignment, you will:

Build a chord recognizer and evaluate its constituent parts.
1. Open Google Colab and create a notebook that you'll use for shell commands
Log in to your NJIT email, and go to colab.research.google.com and create a new Jupyter notebook. You will use this notebook for cloning the assignment repository.

2. Mount your google drive
In a new cell, run the following code:

from google.colab import drive
drive.mount('/content/drive')

This will mount your Google Drive. Note that you may be required to grant permissions to your drive. You can then view the drive folders by clicking on the Files tab on the left of your screen.

cd into your class directory, cd /content/drive/MyDrive/MachineListening-Fall2022.

3. Clone this repository
Using your personal access token you generated in HW0, clone this repository, execute the following in an empty cell:

!git clone https://{your_username}:{git_token}@github.com/{your_username}/{repository}

If you forgot your personal access token, go to https://github.com/settings/tokens to regenerate your token.

4. Open the assignment notebook and read through, completing all steps
Open Google Drive and navigate to your MachineListening-Fall2022/hw2-chord-recognition folder.
Open assignment.ipynb in Colab and complete the instructions for the assignment.
To pass the test cases you will edit the files in the src directory.
Do not edit anything in the tests directory. Files can be added to tests but files that exist already cannot be edited.

5. Commit and push to Github
You will need to commit changes and push to Github to submit the code, notebook, and output files. Note that before running the commit command you will need to configure git with your email and name, e.g.

!git config --global user.email "you@example.com"

!git config --global user.name "Your Name"

Please refer to the git documentation and book for how to add files, commit changes, and push.

Questions? Problems? Issues?
Please make sure first that something in this document doesn't already address your issue! If you still have problems, simply open an issue on the starter code repository for this assignment here. Someone from the teaching staff will get back to you through there!
