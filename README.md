# OllamaTutorial

python -m venv venv
Venv\Scripts\activate

pip install -r requirements.txt

python .\sample_request.py 

After project modified:

echo venv/ > .gitignore 
echo __pycache__/ >> .gitignore 
echo *.pyc >> .gitignore

or use https://www.toptal.com/developers/gitignore/ to create the gitignore file

Register at gighub for the project, create new respository, run
Git init
git remote remove origin
Git remote add origin https://github.com/joexgit2024/OllamaTutorial-modified.git
Git add .
Git commit -m "modified files for the project"
Git push -u origin main![image](https://github.com/user-attachments/assets/9cdd6a3e-a35b-4b80-9e3a-a526a4e91eae)
