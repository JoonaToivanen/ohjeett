# Ohjeet Gitin ja GitHubin käyttöön

![](https://github.com/JoonaToivanen/ohjeett/blob/main/GitHub-logo.png)

## Gitin ja GitHubin alustus

Lataa ja asenna [Git](https://git-scm.com/) 


Rekisteröidy [GitHubiin](https://github.com/)


Määritä Gitin asetukset:


`git config --global user.name "Nimesi"`


`git config --global user.email "sähköposti@esimerkki.com"`


# Git-repositorion luominen


Luo paikallinen Git-repositorio:


`git init`


# Työskentely Gitin kanssa


Tarkista tiedostojen tila:


`git status`


Lisää muutokset indeksiin:


`git add tiedosto.txt`  # Yksittäinen tiedosto


`git add .`  # Kaikki muutokset


Tee commit muutoksille:


`git commit -m "Lyhyt viesti commitille"`


# Työskentely GitHubin kanssa


Luo uusi repositorio GitHubiin:


Mene GitHubiin ja klikkaa "New" luodaksesi uuden repositorion.


Yhdistä paikallinen repositorio GitHubiin:



`git remote add origin https://github.com/käyttäjänimi/repository.git`


Puske muutokset GitHubiin:


`git push -u origin main`  # Tai master, riippuen repositorion asetuksista


# Päivitykset GitHubista (pull)


Vedä uusimmat muutokset GitHubista paikalliselle koneelle:



`git pull origin main`  # Tai master


# Haara (branch) käyttö


Luo uusi haara:



`git branch uusi-haara`


Siirry haaran päälle:



`git checkout uusi-haara`


Yhdistä haara (merge) takaisin päähaaraan:



`git checkout main`  # Siirry päähaaraan


`git merge uusi-haara`


# Välimuisti ja yhteenveto


Katso Gitin historia:


`git log`


Poista tiedosto Gitin seurannasta:


`git rm --cached tiedosto.txt`
