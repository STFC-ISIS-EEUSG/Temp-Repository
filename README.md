Create using command line

echo "# Temp-Repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/STFC-ISIS-EEUSG/Temp-Repository
git push -u origin main
