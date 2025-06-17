GitHub Tutorial repository
Trying GitHub to save other usefull repositories about
  Python
  TensorFlow
  Keras
  RNN
  NN
  DataScience
   

# Git rename branch to Main
1. rename your local branch:
   ``` git branch -m master main  ```
2. change the tracked branch
 ``` git fetch -p origin   ```
 ``` git branch -u origin/master main  ```
3. change the main local branch
 ``` git remote set-head origin -a  ```

4. optionally, remove the master branch, local and remotely:
 ``` git branch -D master  ```
  ``` git push origin :master  ```
