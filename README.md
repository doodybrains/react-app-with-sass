This a basic react boiler plate created with Create React App : https://github.com/facebookincubator/create-react-app

INSTRCTNS:

1. Node 6 & NPM 3 recommended
2. switch "homepage" url in package.json to gh-pages url
3. npm install
4. npm start to see local
5. npm run build to build app for deployment
6. to deploy follow steps 7-12
7. git checkout -B gh-pages
8. git add -f build
9. git commit -am "Rebuild website"
10. git filter-branch -f --prune-empty --subdirectory-filter build
11. git push -f origin gh-pages
12. git checkout -
