# React App 

[Example deployment React App with GitHub Pages](https://saramazal.github.io/mazal-todo-list/)

* 1. git remote add origin git@github.com:{username}/{repo-name}.git
* 2. git add .
* 3. git commit -m "commit"
* 4. git push -u origin main 
* 5. Add properties to package.json file:
     - "homepage": "http://{username}.github.io/{repo-name}",
* 6. - npm install gh-pages --save-dev
* 7. Add properties to "scripts":
     {
      //...
        "predeploy": "npm run build",
        "deploy": "gh-pages -d build",
      }
* 8.  npm run deploy
* 
![Screenshot](https://github.com/saramazal/mazal-todo-list/blob/main/mazal-todo-list.png)
