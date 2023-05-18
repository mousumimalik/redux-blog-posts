# redux-blog-posts

Deploy Guide :

1. Push code to github using Git Command

2. install - npm install gh-pages --save-dev

3. Add in package.json - "homepage": "https://mousumimalik.github.io/name-of-your-repo",

4.  Add in package.json -
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
    
5. Add in cmd -
    git add .
    git commit -m "Deployed"
    git push
    
6. npm run deploy
