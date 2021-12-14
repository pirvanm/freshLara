#1 Instalare Tool
https://laragon.org/download/ Laragon Full: Apache 2.4, Nginx, MySQL 5.7, PHP 7.2, Redis, Memcached, Node.js 11, npm, yarn, git,…

După cum se poate observa avem “preinstalat” git  altfel îl putem insta și fără laragon folosindu-ne de : 
#2 La un moment dat o sa ne afișează următorul mesaj

*** Please tell me who you are.
 Run git config --global user.email "you@example.com" 

git config --global user.name "Your Name"

Pentru a merge la sigur, putem pe pasi sa scriem in terminal :
git config --global user.email "pirvan.marian@gmail.com"
 git config --global user.name "Pirvan Marian"

Important : asta ne cere doar odata, atunci cand instalam git pentru prima data, daca ne cere a doua oara inseamna ca nu am completat sau avem 2 conturi diferite de git, ceea ce nu e ok.


#3 Sincronizarea cu Repo Extern

Pentru a simplica totul vom face git clone de repository-ul nostru :

git clone https://github.com/pirvanm/porto , vom primia acces la el daca este public si daca administratorul nu pus tot felul de limitari, recomandat este ca un repostitory sa fie privat si sa invitite un colaborator pe proiectul sau.


Optional
 
 In mod standard trebuie sa ne conectam /sincronizam cu un repository remote de pe un site precum github.com /bitbucket / sau gitlab.com , e prea complicat dar daca suntem curiosi 
https://docs.github.com/en/free-pro-team@latest/github/using-git/adding-a-remote

$ git remote add origin https://github.com/user/repo.git
# Setare un nou repo

#4 Inregistrarea Datelor 
Pentru a intra in zona “track a file” il adaugam folosind git add numefisier sau 
git add * pentru toate

git commit -a -m’ pentru a pune un mesaj’


#5 Trimitere date pe un repo
pentru a trimite toate datele nu trebuie decat sa facem  :git push


#6 Ultimele actualizari
Cand cineva face modificari si vrem sa le salvam avem :
git pull 

Este important, sa fim in directorul unde se afla si proiectul nostru sincronizat cu git, deoarece unde este stocata aceasta informatie.

In folderul .git…, folder ce se creaza automat la clonare…

daca nu merge git push ,da eroare cu 13 august… 
du-te pe 
https://github.com/settings/profile

in stanga e un meniu cu link developer setting  care te duce pe :

https://github.com/settings/apps

Clicl pe personal access token

ne duce pe https://github.com/settings/tokens/new
bifam optiunile si click pe generate token 
