#check python3.14* installed or not

#create venv
python3 -m venv .cmsp_venv


# Windows: 
(run only first time)
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser


(run every time before working on this project)
.cmsp_venv\Scripts\activate
# Mac/Linux: 
source .cmsp_venv/bin/activate


#install requirements:
pip install -r requirements.txt


#before closing VSCode deactivate the environment: 
deactivate
