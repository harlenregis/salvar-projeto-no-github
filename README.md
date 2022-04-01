git config --global user.name <seu nome>
git config --global user.email <seu email>

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:harlenregis/gestao-festa.git (Tem que está no SSH)
git push -u origin main

git status
git add .
git commit -m "alteração"
git push
