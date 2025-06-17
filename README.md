GitHub Tutorial repository
Trying GitHub to save other usefull repositories about
  Python
  TensorFlow
  Keras
  RNN
  NN
  DataScience
   

# Git rename branch to Main
1. rename your local branch: <br>
 ``` git branch -m master main  ``` <br>
2. change the tracked branch <br>
 ``` git fetch -p origin   ``` <br>
 ``` git branch -u origin/master main  ``` <br>

3. Push the new branch to the remote repository
 ``` git push origin main ```

4. change the remote default repo going to:  https://github.com/[username]/[repo]/settings 
  > Default branch <br>
   > Switch to another branch <br>

5. change the main local branch upstrem to match remote <br>
 ``` git branch --set-upstream-to=origin/main main  ``` <br>
