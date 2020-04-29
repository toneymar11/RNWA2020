# RNWA2020

### Upute za instalaciju ###

1. Odabrati direktorij gdje ćete spremiti sve vježbe
2. Postaviti korisničko ime i email
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
3. Klonirati remote repozirotij na svoje računalo
```
git clone https://github.com/toneymar11/RNWA2020.git
cd RNWA2020
```
4. Inicijalizirali lokalni git repostorijum
```
git init
```
4. Dodati udaljeni git repositorijum
```
git remote add RNWA2020 https://github.com/toneymar11/RNWA2020.git
```

### Slanje zadaće na udaljeni repositorijum
1. Provjeriti promjene s naredbom git status
```
git status
```
Rezultti bi trebao biti kao na slici

![alt text](https://raw.githubusercontent.com/fsr-sp/sp-vjezbe/master/images/git_status.png)

2. Spremiti sve datoteke na kojima ste napravili izmjene u Index
```
git add RNWA2020/index.html
git add RNWA2020/assets/main.css
```
3. Nakon što smo dodali datoteke spremi smo za commit. Git status bi trebao izgledati ovako:

![alt text](https://raw.githubusercontent.com/fsr-sp/sp-vjezbe/master/images/git_added.png)

4. Spremiti izmjene
```
git commit -m "Ovdje napisti ime commit-a"
```

5. Slanje lokalnih promjena na vaš udaljeni repozitorij

```
git push
