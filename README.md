1️⃣ Initialize git (if not already)

From your project root (C:\Users\miki\Downloads\Programs\Pr_plugin\FX Studio):

git init 

2️⃣ Set up .gitignore

Create a .gitignore file in the project root with entries like this:

3️⃣ Add remote 
git remote add origin https://github.com/mikiboii/Nova.git
 4️⃣ Add files 
 git add . 
 5️⃣ Commit 
 git commit -m "Initial commit of Nova" 


 6️⃣ Push to GitHub 

 git branch -M main 
 git push -u origin main



******* only on new gits

git push -u origin main --force
*******

Regular commits
git add .
git commit -m "finishing for ae"
git push

new version commit
Modify your code as usual.

Stage and commit your changes:

git add . git commit -m "new ae support"

Tag the new version (like v1.1):

git tag -a v1.0.2 -m "Version 1.0.2 – comment "

Push the tag to GitHub:

git push origin v1.0.2

Run dev server
npm run dev



$env:NODE_OPTIONS="--openssl-legacy-provider"