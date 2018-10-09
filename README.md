# Spikker

## Üldine, kommenteeritud

echo "# meelespea" >> README.md -- seda ei ole vaja käsureale kirjutada
**git init** -- seda teed ainult esimesel korral
**git add README.md** -- kui lisad kõik selle kausta failid, siis käsk on: **git add .**
**git commit -m "first commit"** -- selline sõnum on ainult esimesl commitil, edaspidi muuda sõnumi tekst vastavalt sellele, mida failis muutsid
**git remote add origin https://github.com/mairisaar/meelespea.git ** -- see käsk ainult esimesel korral sellesse repositooriumisse midagi lisades
**git push -u origin master** -- iga kord 

## Uue repositooriumiga esimesel korral järjekord

0. lood uue repositooriumi 
1. git init 
2. nano .gitignore -- kui on nt pildifaile, mida ei taha lisada
3. git add .
4. git commit -m "first commit"
5. git remote add origin https://github.com/mairisaar/meelespea.git
6. git push -u origin master

## Pärast iga muudatust, mida soovid uuendada repositooriumis

1. git add .
2. git commit -m "sõnum selle kohta, mida muutsid"
3. git push -u origin master

## Käsk staatuse küsimiseks

git status