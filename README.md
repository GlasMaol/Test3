# Test3
echo "# fileName" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/GlasMaol/table.git
git push -u origin main


Addera filer till Github repo från datiorn:
git add .
git commit -m "choose comment"
git push


Pull/clone projekt från Remote to main.

Om redan i en fill skriv följande för att gå tillbaka ett steg till main local:
cd ..

Go sedan till remote och kopiera url som finns under gröna Code knappen.

I main skriv:
git clone < din url>

Nu ska allt finnas på local main i en mapp med namnet av den clonade.

