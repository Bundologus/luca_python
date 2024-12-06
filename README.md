# Install
- Git x64-es verzió telepítése [innen](https://git-scm.com/downloads/win)
- Notepad++ letöltése [innen](https://notepad-plus-plus.org/downloads/v8.7.4/)
- cmd-ben leklónozni a repót, beállítani a git configot
```
git clone git@github.com:Bundologus/luca_python.git
cd luca_python
git config add user.name <username>
git config add user.email <user@mail.com>
```

# CMD alapok (avagy: parancssor, terminál, konzol)
- helyi fileok listázása ```dir```
- navigálás a könyvtár struktúrában ```cd cél\könyvtár\mappa```
  - teljes elérési úttal ```cd C:\Users\Public```
  - relatív elérési úttal egy mappával feljebb ```cd ..``` >> *C:\Users\Public*-ból *C:\Users*-be visz
  - relatív elérési úttal ```cd .\Public``` >> *C:\Users*-ből *C:\Users\Public*-ba visz
- meghajtó váltás mondjuk F:-e ```F:```
- parancssori program futtatása ```<programnév> <kapcsolók> <paraméterek>```, de ez néha eltér, érdemes a helpet elolvasni
- hasznos programok:
  - ```mkdir <name>``` új mappa létrehozása <name> névvel a jelenlegi könyvtárban
  - ```rmdir <name>``` mappa törlése, ha üres
  - ```rmdir \S <name>``` \S kapcsolóval nem üres mappát is töröl
  - ```type nul > your_file.txt``` üres file létrehozása, bármilyen névvel, kiterjesztéssel
  - ```echo "hello world!" >> output.txt``` szöveg kiíratása már létező file végére, vagy új fileba
  - ```echo "hello world!" > output.txt``` így pedig felülírja, ha már van ilyen file.
  - ```type oputput.txt``` file tartalmának kiíratása a konzolra
  - ```output.txt``` file megnyitása

# Python
- verziószám ellenőrzése ```python -V```
- python script file futtatása ```python <elérési_út>.py```
- cheatsheet [1/2](https://miro.medium.com/v2/resize:fit:4800/format:webp/1*c5VpifqGLLCUTY5Ri5Yd2Q.jpeg) [2/2](https://miro.medium.com/v2/resize:fit:4800/format:webp/1*jVQFksUBtjGNZvQ6FG0bbQ.jpeg) 

# Git alap parancsok
- ```git clone <repo_path>``` repository letöltése
- ```git add <elérési_út>``` egy vagy több file/mappa hozzáadása a verziókezelőhöz
- ```git commit -a -m"message"``` a workspace lokális állapotának regisztrálása
- ```git push``` lokális verzió feltöltése a remote-ra
- ```git switch <branch_name>``` váltás másik branch-re
- ```git pull``` remote változásainak letöltése
- ```git status``` aktuális állapot ellenőrzése
- ```git log``` commint history megtekintése
- [vizuális demo](https://ndpsoftware.com/git-cheatsheet.html#loc=workspace)
