git clone https://github.com/szabopeter92/git-vizsga - le knlónozzuk a git repositorit
cd git-vizsga - belépünk a working directory-ba 
git remote set-url origin https://github.com/BartaKristof/git-vizsga.git - átváltunk a saját git repositorinkra
git status
git add . 
git commit -m "gitignore és README fájl létrehozva"
git branch console - létrehozunk egy új ágat
git checkout console - átváltunk az új ágra
git status 
git add . 
git commit -m "app.js és README fájl módosítva"
git status 
git add .
git commit -m "style.css és README fájl módosítva"