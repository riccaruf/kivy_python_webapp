#create virtual env
python -m venv .venv

#activate local env virtual environment
.\.venv\Scripts\activate

#kivy_deploy.txt the script to recreate the env under https://colab.research.google.com/

#command to run buildozer
! buildozer -v android debug