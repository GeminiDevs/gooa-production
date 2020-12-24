## GOOA WORLD FREIGHTERS

 - This is a simple web app for a company
 - The backend of this web app is powered by The Django Web Framework
 
 ### Contribution
 
 - Fork the repository to your own account. 
 - Clone your fork to your local machine
 - Work on your local repo
 - Push your commits to your remote fork
 - Submit a Pull Request (PR) to the main repo of the organization
 - Await review.

  ### Git workflow
 
 - After forking the repo to your account, clone it using:-
   
    `git clone https://github.com/GeminiDevs/gooa-production.git`

 
 - After which, all code commits should be made on the `slave` branch.
    - Switch to the slave branch using `git checkout slave`
    
    
 - Push your commits using `git push -u origin slave` and submit a PR to the `slave` branch.
 - Do not push to the `master` branch.
 
 ### Running the web app
  
 - Create a virtual environment in your IDE (may come automatic in some e.g Pycharm) or text editor or run the command: 
    ``python -m venv venv``
   

 - Activate the virtual environment by running...
    ``source venv/bin/activate``
   

 - Install all the project dependencies by running...
    ``pip install -r requirements.txt``
   

 - Make the necessary django migrations by running these two commands:
 
    ``python manage.py makemigrations``
    
    ``python manage.py migrate``
   

 - Now run the server and launch the web app using:
 ``python manage.py runserver``
 
 ### Pulling Changes
 - After every PR merge, one should pull the changes in this manner...
 - In your local repo, run the following command:
   
    ``git pull https://github.com/GeminiDevs/gooa-production.git``
   

 - Then push those changes to your remote fork(repo) using:
   
    ``git push -u origin slave``


 - This will even the slave branches of both your fork and this repo. 
 
 
 ##### Thank you for your input and contribution. 
 ##### And remember, it is your GNU-given right to Fork!