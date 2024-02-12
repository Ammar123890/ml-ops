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
    git branch zain

# Switch branches

    git checkout dev
    git checkout zain

# Changing main.py in dev branch use commands
    git add . 
    git commit -m "dev"
    git push origin head

head is use for the current brach

# Check the status for the branh 
    git status

Your branch is ahead of 'origin/master' by 1 commit.
  


 # Checkout to master and merge with dev

    git checkout master
    git merge dev

Auto-merging main.py
CONFLICT (add/add): Merge conflict in main.py
Automatic merge failed; fix conflicts and then commit the result.
    
        
  # Repeat the same steps for the zain branch

  # Now pull the changes to another PC using 
    git pull origin master

From https://github.com/Ammar123890/ml-ops
* branch            master     -> FETCH_HEAD
Updating 5fefbba..629b74f
Fast-forward
main.py | 8 ++++----
1 file changed, 4 insertions(+), 4 deletions(-)

  # Check the difference between the commits    
    git diff HEAD^ HEAD

diff --git a/main.py b/main.py
index bef9e9b..a69a03c 100644
--- a/main.py
+++ b/main.py
@@ -16,10 +16,10 @@ def divide(x, y):


 print("Select operation.")
-print("1.Add")
-print("2.Subtract")
-print("3.Multiply")
-print("4.Divide")
+print("1.+")
+print("2.-")
+print("3.*")
+print("4./")

    
  
    


       



    
