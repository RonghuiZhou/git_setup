# Process to set up Git on your computer

## Change default directory
https://stackoverflow.com/questions/7671461/how-do-i-change-the-default-location-for-git-bash-on-windows


I read it somewhere and it worked for me.

First check in git bash what is the HOME location. Open git bash and run

echo $HOME


Now change the HOME path by opening cmd and run

setx HOME "path/to/.ssh/loc" (I gave C:\Users\aXXXX)
Now cross check by running the echo command in git bash.

setx HOME C:\Users\rzhou11\Desktop\GitHub
