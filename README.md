Git inicializálása a mappában:
git init

.gitignore file létrehozása,
*txt
*doc
*docx
*pdf - kiterjesztésű fájlokat hagyjuk figyelmen kívül.

git status - ellenőrzöm, hogy milyen fájlokban történt változás

git add . - hozzáadom a változtatást a staging areahoz

git commit -m "" - commitolom a local repositoryba a változókat

git status - ismét ellenőrzöm

git remote add origin https: https://github.com/robyee05/mikhelrobert_gitvizsga.git - próbáltam összekapcsolni a saját github fiókommal, de írta hogy már van egy remote origin

git remote remove origin - leválasztom a remote origint

git remote add origin https: https://github.com/robyee05/mikhelrobert_gitvizsga.git - ismét hozzáadom a github fiókom

git push -u origin main - végül feltöltöm a létrehozott repository main ágába.
