## Install virtual enviroment
python -m venv venv
.\venv\Scripts\activate

in the case of error message: "\venv\Scripts\Activate.ps1 cannot be loaded because running scripts is disabled on this system.", run in the PowerSell:
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scoppe CurrentUser

pip list

 ## xlwings
 pip install xlwings
