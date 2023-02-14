alias ls="rm *" : we used this command give the ls a value of rm *
echo "hello $USER" : to print hello + the current linux user
export PATH=$PATH:/action : to add action to the PATH and it will be automatically the last directory
echo $PATH | tr ':' '\n' | wc -l : to count the numbrer of directories in a path
