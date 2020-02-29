* NodeJS >=10

mkdir test-commitlint
cd test-commitlint/
vim README.md
git init
node --version
touch package.json
npm install --save-dev @commitlint/{config-conventional,cli} husky
vim package.json 
npm install --save-dev @commitlint/{config-conventional,cli} husky
cat package.json 
vim package.json 
git status
vim .gitignore
git status
echo "module.exports = {extends: ['@commitlint/config-conventional']}" > commitlint.config.js
vim package.json 
git add .
git commit -m "test"
