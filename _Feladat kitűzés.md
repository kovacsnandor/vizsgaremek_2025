# Tartalom
- [Tartalom](#tartalom)
- [Ütemezés](#ütemezés)
    - [2023.02.20-26](#2023.02.20-26)
- [Általános feladtok](#általnos-feladtok)
  - [Fejlesztési környezet](#fejlesztési-környezet)
  - [Egyéb előírások](#egyéb-előírások)

- [Recept](#recept)
- [História](#história)
- [Sportverseny](#sportverseny)
- [Film](#film)
- [Kölcsönzés](#kölcsönzés)

# Vizsgakövetelmények
## csapat, feladat, határidő
- A vizsgázóknak **minimum 2, maximum 3 fős** fejlesztői csapatot alkotva kell a vizsgát megelőzően 
- egy komplex szoftveralkalmazást (vizsgaremek) fejleszteniük 
- a tanév során
- Beadás: a vizsgát megelőző 14 nap, GITHUB platformon.

## Elvárások
- **Életszerű**, valódi problémára nyújt megoldást. 
- Adattárolási és -kezelési funkciókat is megvalósít (**CRUD**). 
- **RESTful** architektúrának megfelelő **szerver és kliens oldali** komponenseket egyaránt tartal-maz. 
- A forráskódnak a **tiszta kód elveinek** megfelelően kell készülnie. 
- A szoftver célját, komponenseinek technikai leírását, működésének műszaki feltételeit és használatának rövid bemutatását tartalmazó **dokumentáció** is része a csomagnak. 

### Kliens oldal
- Alkalmasnak kell lennei asztali és mobil eszközökön történő használatra. 
- Mobil eszközre kifejlesztett kliens esetén natív mobil alkalmazás, vagy azzal hozzávetőlegesen megegyező felhasználói élményt nyújtó webes kliens egyaránt alkalmazható. 
- Asztali eszközökre fejlesztett kliens oldali komponensnél mindenképpen szükséges webes megvalósítás is, de emellett opcionálisan natív, asztali alkalmazás is a cso-mag része lehet. 
- Példa: A felhasználóknak szánt interfész webes megjelenítést használ, míg az adminisztrációs felület natív asztali alkalmazásként készül el 

## Tartalmi követelmény
- A megosztott anyagnak tartalmaznia kell az alábbiakat: 
    - A szoftver **forráskódja**, 
    - Natív asztali alkalmazások esetén a program telepítőkészlete, 
    - Az adatbázis **adatbázismodell**-diagramja, 
    - Az adatbázis export fájlja (**biztonsági másolat**), 
    - A szoftveralkalmazás **dokumentációja**, 
    - A **tesztekhez végzett kód**, 
    - valamint a **teszteredmények dokumentációja**. 

## Vizsgaremek bemutató
- A vizsgarész során a vizsgázó gyakorlati bemutatóval összekapcsolt **szóbeli előadás** formájában mutatja be a 
    - szoftver célját, 
    - műszaki megvalósítását, 
    - működését, 
    - forráskódját, 
    - a csapaton belüli **munkamegosztást**, a fejlesztési csapatban betöltött szerepét, a fejlesztés so-rán használt projektszervezési eszközöket. 
- A fentieken túl maximum **3-5 perces angol nyelven** tartott szóbeli előadás formájában **összefoglalót** ad a szoftver céljáról és működéséről
- valamint **angolul válaszol** a vizsgáztató végfelhasználói szerepben feltett maximum 2-3 kérdésére.
- a bemutatót **közösen is megtarthatják**, 
    - minden vizsgázó **egyenlő arányban** vegyen részt a bemutatóban, 
    - minden vizsgázónak **önállóan kell bemutatnia a saját feladatrészét** 
    - magyarul és angolul egyaránt.

## Vizsgaremek pontozás
- a szoftver átfogó értékelése (a választott téma életszerűsége, az elkészült szoftver hasz-nossága, a komplexitás és kidolgozottság mértéke, milyen mértékben és minőségben valósította meg a szoftver a kitűzött célt, felhasználói élmény minősége): 5 pont 
- adatbázis-tervezés és megvalósítás: 5 pont 
- szerver oldali komponens (backend): 10 pont 
- asztali használatra készült kliens oldali komponens (frontend): 10 pont 
- mobil használatra készült kliens oldali komponens: 10 pont 
- a kód minősége: 3 pont 
- a dokumentáció minősége és részletezettsége: 2 pont 
- a szoftver tesztelésének bemutatása: 3 pont 
- a szoftver bemutatása során a vizsgázó előadásának szakszerűsége, illetve az angol nyelvű kommunikáció minősége: 3 pont 
- a csapatmunka megvalósítása: 4 pont 

# Ütemezés
## 2025. janauár vége környezet
- feladat megértés
- ütemterv elkészítés
- kommunikációs környezet kialakítás
- github saját repó létrehozás
- fejlesztési környezet létrehozás
## 2025. február adatbázis, backend
- adatbázis tervezés
- migráció
- diagram
- seederek
- teszt és éles adatbázis
- felöltés teszt adatokkal (tárolt eljárással)
- hitelesítés
- crud endpointok
- query endponintok
- kézi tesztek (request.rest)
- tesztek
    - unit
    - funkcionális
    - integrációs
- backend dokumentálás    
`document_database/projektnev.sql`

## 2025. március frontend
- frontend környezet felállítás
- menü szerkezet
- crud műveletek
- egyéb műveletek
- frontend tesztek
    - unit
    - funkcionális
    - integrációs
- frontend dokumentálás
## 2025. április
- utolsó simítások
- dokumentáció befejezés
- előadás elkészítése (ppt)
- előadás gyakorlása
    - angol nyelvű rész
    - magyar nyelvű rész
    - szereposztások

# Általános feladtok
A feladatot az alábbi előírásoknak megfelelően kell elkészíteni

## Fejlesztési környezet
- gitHub repo: 
    - kötelező
    - itt kell fejleszteni
    - a repo neve: a feladat neve
    - `RADME.md`
        - Mi ez a program
        - Itt kell leírni, hogy a feladatot hogy kell üzembe helyezni
    - `Technical description.md` (Műszaki leírás)
        - Le kell írni struktúráltan hogy működik a feladat, magyar nyelven.
        - Mappa struktúra
        - Adatbázis 
            - diagram
            - Teszt adatok
        - Backend leírása
            - sql gyűjtemény
            - Milyen modulok
            - Milyen fájlok
            - Data server
                - .env
                - Kapcsolódás az adatbázishoz
                - get, post, put, delete
                - middleware
                    - json
                    - cors
                    - autentikáció
            - Auth server
                - Bejelentkezés
                - Token
            - pingelés (request rest)


        - Frontend leírás
            - Mi a program célja
            - Milyen modulok
            - Milyen fájlok
                - store
                - komponensek
                - views
                - router
                - Oldal szerkezet
                    - Belépési pont: App.vue, main.js
                    - Head
                    - Menü
                    - Tatalom


    - `Users Guide.md` (Használati útmutató)
        - Le kell írni, képernyő képekkel hogy a produktumot hogy kell használni
    - `Presentation.ppt`  
        - Egy max 15 perces bemutató előadást támogató prozentáció
            - Személyes bemutatkozás
                - Mi a szakterület, mihez értek
                - Milyen terveim vannak
            - Mi a feladat célja
                - mit csinál
                - mit tud aprogram
                - bejelentkezés
            - Mi a feljesztési környezet
                - pl. Mysql adatbázis, Vusj kliens, Nodejs Backend, github
            - Milyen az adatbázis 
                - diagram, 
                - teszt adatok
                - Anyaggyűjtés
            - Be kell mutatni működés közben
            - Meddig jutottam el
            - Milyen irányban kell továbbfejleszteni
            - Egy kód részletet kiemelni és bemutatni

    - dokumentációs mappák:
        - `document_database`
            - `adatbázis modellje`: kép és fájl
            - `projektnev.sql`
                - Adatgerenerálás: tárolt eljárások, függvények
                - A backendben használt sql lekérdezések
            - biztonsági mentés
        - `server` mappa
            - Legyen egy adat szerver
            - Autentikációs szerver
            - npm csomagkezelés
        - `frontend` mappa
            - ide kerüljön a frontend, 
            - ami lehet teljesen független a szervertől
            - nem kötelező, hogy a szerver publikálja
            - npm csomagkezelés

## Egyéb előírások
- nyelvi előírások
    - Az objektumok (adatbázis, mező nevek, függvények, vátlozók stb. ) elnevezései angol nyelvűek.
    - A produktum működési felülete akármilyen nyelvű lehet.
    - Az adatbázis kódolásakor tartsa be a tiszta kód elveit.

- Működési környezet
    - A produktum elég, ha a feljesztő környezetben működik, nem kell élesben telepíteni.

- Autentikáció kötelező javasolt: jwt token
    - users tábla
    - Regisztráció
    - Login
    - Logout
    - Jogosutsági szintek
        - adminisztrátor: teljes joggal szerkesztheti az adatokat
        - vendég: olvashatja az adatokat
        - Az oldal betöltésekor kötelező vagy regisztrálni, vagy belépni.

# Recept
Csapattagok: Fehér Zsolt Dorián, Juhász Gergő
![adatbázis modell](_sources/Recept/recept.jpg)

# História
**Csapattagok**: Kovács János, Jáger Kristóf

Egy történelemmel foglalkozó adatbázist szertnénk létrehozni, aminek fő célja, hogy segítse az érettségire készülő diákokat.
- Lenne egy beviteli felülete, amint keresztül tananyagot lehetne feltölteni, megjelölve a forrásokat.
- Ezen túl előre kidolgozott tesztek segítenék a tanulást. A diákoknak nyújtanák véletelenszerű vagy tematikus név, évszám teszteket.
![adatbázis modell](_sources/Historia/historia.jpg)

# Sportverseny

**Csapattagok**: Medgyes Csaba, Ledacs-Kiss Bence

Egy excel táblában szemléletett sportverseny szisztémát kéne megvalósítani, amivel egy iskolai rendezvény szervezését bonyolítanánk le.
A szisztéma lényege: 
- különböző állomásokon különféle sportágak, feladatok várják a résztvevőket.
- Egy csoport tagjainak eredményeit (idő, távolság, pontszám stb.) összegzik
- A program az így összesített eredményeket az adott helyszínen csökkenő sorrendben rakja és aki első az kapja a legtöbb pontot, és ha kell súlyozza.
    - A pontszám megyegyezik azzal a számmal, hogy a listában hanyadik
    - A praméterezésben meg lehet adni, hogy az eredményeket csökkenő, vagy növekvő sorrendbe kell rendezni.
- A végén a rengsor pontokat csapatonként összegzi, és így alakul ki a végső rangsor.
![adatbázis modell](_sources/Sportverseny/sportverseny.jpg)

# Film
Csapattagok: Molnár Krisztián, Hajdu István, Polyák Alex János
![adatbázis modell](_sources/Film/film.jpg)


# Kölcsönzés
Csapattagok: Oláh Péter, Nagy Ferenc
![adatbázis modell](_sources/Kolcsonzes/kolcsonzes.jpg)


