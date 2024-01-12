# ToDo-List
 - This is a Basic Todo-List
# How to clone in Node JS
1. Open Terminal or Command Prompt and navigate to the directory where you want to create your project.
2. Run command: `git clone https://github.com/aligates915/todo_list.git` (Make sure that you are connected to Internet)
3. After cloning process is complete, navigate into the project folder by running `cd todo_list`.
4. run npm init  in your project directory to generate a package.json file.
5. run npm install webpack webpack-cli --save-dev to install webpack to the node_modules directory of your project.

6. Quick tip: the node_modules folder can get really big. It is customary to add a .gitignore file to your project so that you don’t have to sync the contents of node_modules to github. The dependencies that are stored there can be installed from your package.json by running npm install, so you don’t need to sync them.

7. run command npx webpack --watch
git init
Add Remote Repository:
Add the remote repository URL of your GitHub repository. Replace <repository-url> with the actual URL of your GitHub repository.
https://github.com/AliGates915/TO-Do-List/tree/master
git remote add origin <repository-url>
Stage Changes:
Stage the changes you want to commit. You can do this using the following command:

git add .
This stages all changes. If you want to stage specific files, replace . with the file names.

Commit Changes:
Commit the staged changes with a meaningful commit message
git commit -m "Your commit message here"
Push Changes:
Push the committed changes to the remote repository:
git push -u origin master