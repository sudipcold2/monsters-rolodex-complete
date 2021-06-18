# DEMO REACT APP DEPLOYMENT WITH GITHUB PAGES

---

## Add gh-pages dependency
   npm install --save gh-pages

## Add two scripts in scripts of package.json 
   "scripts":{ 
    ...
    ...
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
   }

## Add Homepage in package.json
    "homepage": "https://sudipcold2.github.io/monsters-rolodex-complete/"

## Run "npm run deploy" 
    