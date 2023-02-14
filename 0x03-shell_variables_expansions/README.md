alias ls="rm *" : we used this command give the ls a value of rm *
echo "hello $USER" : to print hello + the current linux user
export PATH=$PATH:/action : to add action to the PATH and it will be automatically the last directory
echo $PATH | tr ':' '\n' | wc -l : to count the numbrer of directories in a path
printenv : to display environment variables (Global variables)
BEST="School" : to creat a local variable named BEST with the value School
export BEST="School" : to creat a Global var named BEST with value School

