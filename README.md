# Zindi-User-Behaviour-Birthday-Challenge
Can you predict which users will be active on Zindi in the next month?

https://zindi.africa/competitions/zindi-user-behaviour-birthday-challenge

<img src="image.png">


## Steps to reproduct the final solution:

1. Create a new environment in conda with the dependencies

   > conda create --name <environment_name> python=3.7 
   
   > conda activate <environment_name>
   
   > pip install -r requirements.txt

2. Create a folder `data` and add all competition files to this folder
3. Create another folder `outputs`. This folder will contain the output.
4. Run the notebook `modeling.ipynb`
5. The final output is stored in `./outputs/final_sub_v1.csv` after the notebook has completed running
