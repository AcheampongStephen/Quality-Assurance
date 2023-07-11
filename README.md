1. Create and activate environment

- conda create -n wine-quality python=3.8 -y
- conda activate wine-quality

2. Create the project template

- Folders
- Files

3. Install the dependencies

- pip install -r requirements.txt

4. Download the dataset

- https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

5. Initiate Git

- git init

6. Initiate DVC

- dvc init

7. Track/Version data using DVC

- dvc add data_given/winequality.csv

8. Add and Commit the changes using git

- git add .
- git commit -m "first commit"

9. Add and Commit the changes using git repository

- git remote add origin https://github.com/AcheampongStephen/Quality-Assurance.git
- git branch -M main
- git push -u origin main

10. Get and load the data
11. Reproduce the stage using DVC

- dvc repro
