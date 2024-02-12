# create the repo using gh

    gh repo create ml-ops --public

# Initalize the repo

    git init 
    Initialized empty Git repository in C:/Users/syeda/OneDrive/Desktop/MLOPS/.git/

# Add remote origin 

    git remote add origin https://github.com/Ammar123890/ml-ops.git

# Staging

    git add .     

# Comiting
    
    git commit -m "Initial commit"

# Pushing 
   
    git push -u origin master

# Creating two new branches

    git branch dev
    git branch test

# Switch branches

    git checkout dev
    git checkout test

# Changing main.py in dev branch use commands
    git add . 
    git commit -m "dev"
    git push origin head

        ## head is use for the current brach


 # Checkout to master and merge with dev

    git checkout master
    git merge dev
       



    
