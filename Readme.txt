git init
git remote add origin <repo link>
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
git checkout -b YOURLASTNAME_B1
git add Profile.txt
git commit -m "Added amendments in Profile.txt"
git push origin YOURLASTNAME_B1
git checkout -b YOURLASTNAME_B2
git add Education.txt
git commit -m "Added amendments in Education.txt"
git push origin YOURLASTNAME_B2
git checkout -b YOURLASTNAME_B3
git add Background.txt
git rm Test.py
git commit -m "Amendments in Background.txt and removed Test.py"
git push origin YOURLASTNAME_B3
git checkout -b YOURLASTNAME_B4
git add Readme.txt
git rm Test.py
git commit -m "Added Git commands in Readme.txt and removed Test.py"
git push origin YOURLASTNAME_B4
