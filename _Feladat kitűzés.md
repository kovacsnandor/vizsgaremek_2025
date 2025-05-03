
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
- github repó létrehozás, kollaboráció megvalósítása
- kommunikációs környezet kialakítás
- ütemterv elkészítés
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
### gitHub repo: 
- kötelező
- itt kell fejleszteni
- a repo neve: a feladat neve
Két mappa:
- `Backend`
- `Frontend`
### Dokumentumok
A dokumentumok a repo gyökér könyvtárába kerüljenek, pontosan ilyen elnevezésekkel

- `RADME.md` (A szoftver működésének műszaki feltételei)
    - A fejlesztési környezethez szükséges szoftverek
    - Forráskód letöltése
    - A program teszt környezetéenk telepítése, futtatása

- `Dokumentáció.md` (A szoftver célja, komponenseinek technikai leírása, használatának rövid bemutatása)
    - A szoftver célja: A feladat rövid leírása
    - Használatának rövid bemutatása: Képerynőképekkel, hogy működik a program
    - komponenseinek technikai leírása: 
        - Mappa struktúra
        - Adatbázis 
            - diagram
            - Tábla és mezőleírások
        - Backend
            - endpointok
            - Auth server
                - Bejelentkezés
                - Token

        - Frontend leírás
            - Mi a program célja
            - Használati útmutató
                - Le kell írni, képernyő képekkel hogy a produktumot hogy kell használni
            - Milyen modulok
            - Oldal szerkezet
                - Belépési pont: App.vue, main.js
                - Head
                - Menü
            - Jogosultsági rendszer kezelése
                - Backend szinten
                - Menü szinten
                - Route szinten   
            - Milyen fájlok
                - store
                - komponensek
                - views
                - router
- `Tesztek.md` (A tesztekhez végzett kód, valamint a teszteredmények dokumentációja)
    - Kézi teszt: pingelés (request rest)
        - request.rest szerkezete
        - Bejelentkezés
        - Minta kód CRUD műveletekre
    - Backend tesztek
        - Unit tesztek
        - Funkcionális tesztek
        - End-point tesztek
        - Teszt lefutási képernyőkép dokumentálása
    - Frontend tesztek
        - Teszt fajta megnevezése
        - A tesztek kódja
        - A teszt eredményének dokumentálása

- `Diagram.png` (Az adatbázis adatbázismodell-diagramja)
- `AdatbazisBackup.sql` (Az adatbázis export fájlja)


# Az előadást segítő eszközök
Ez már ne legyen a repóban

- `Presentation.ppt`  
    - Egy max 30 perc/fő bemutató előadást támogató prozentáció
        - Célszerű lenne felváltva beszélni
        - Személyes bemutatkozás
            - Mi a szakterület, mihez értek
            - Milyen terveim vannak
        - Mi a feladat célja általánosan, világosan
            - mit csinál
            - mit tud a program
            - milyen szerepkörök vannak
        - Csapatmunka bemutatása
            - Ki mit csinált: munkamegosztás
            - Milyen csapatmunka eszközöket használtatok
                - Feladat kiosztás
                - Kommunikáció
        - Milyen fejlesztési eszközöket, technológiát használtatok
            - pl. Mysql adatbázis, Vusj kliens, Nodejs Backend, github
        - Az adatbázis bemutatása
            - Diagram, táblák feladatai
            - A táblák és a szerkezetük
            - Honnan származnak az adatok       
            - Volt-e vbalmilyen plusz adatgyűjtés
        - A program működés közbeni bemutatása (`anglul`) (3-5 perc/fő)   
            - Felváltva, vagy valamilyen felosztás szerint            
            - bejelentkezés
            - Menü szerkezet
            - Mit tud a program
            - Milyen műveleteket lehet végezni
            - A reszponzivitás bemutatása (teszt környezetben)
        - Meddig jutottatok el
        - Mi az, amivel esetleg nem végeztetek (ha van ilyen)
        - Milyen irányban kell továbbfejleszteni
        - Egy-egy kód részletet kiemelni és bemutatni példák (amiről lehet beszélni)
            - Backend
                - Mappa szerekezet
                - Forrás adatok
                - Backend technológia (laravel)
                - Migráció
                - Seeder
                - Bejelentkezés, token
                - Endpointok
                - Kontrollerek: CRUD műveletek, speciális lekérdezések
                - Validálás
                - MiddleWare: védett tartalmak kezelése
                - Kézi tesztelés
                - Tesztek bemutatása
            - Frontend
                - Mappa szerkezet
                - A program belépési pontja
                - Menü - rout megvalósítás
                - Bejelentkezés, regizstráció, logout
                - Crud műveletek megvalósítása
                - Kliens oldali validáció az űrlapokon
                - Ajax kérések
                - Speciális feladatok
                - Kliens oldali tesztek


# Egyéb előírások
- nyelvi előírások
    - Az objektumok (adatbázis, mező nevek, függvények, vátlozók stb. ) elnevezései angol nyelvűek.
    - A produktum működési felülete akármilyen nyelvű lehet.
    - Az adatbázis kódolásakor tartsa be a tiszta kód elveit.

- Működési környezet
    - A produktum elég, ha a feljesztő környezetben működik, nem kell élesben telepíteni.

- Autentikáció kötelező
    - users tábla
    - Regisztráció
    - Login
    - Logout
    - Jogosutsági szintek
        - adminisztrátor: teljes joggal szerkesztheti az adatokat
        - vendég: olvashatja az adatokat
        - Az oldal betöltésekor kötelező vagy regisztrálni, vagy belépni.

# A kiosztott feladatok

## Recept
Csapattagok: Fehér Zsolt Dorián, Juhász Gergő
![adatbázis modell](_sources/Recept/recept.jpg)

## História
**Csapattagok**: Kovács János, Jáger Kristóf

Egy történelemmel foglalkozó adatbázist szertnénk létrehozni, aminek fő célja, hogy segítse az érettségire készülő diákokat.
- Lenne egy beviteli felülete, amint keresztül tananyagot lehetne feltölteni, megjelölve a forrásokat.
- Ezen túl előre kidolgozott tesztek segítenék a tanulást. A diákoknak nyújtanák véletelenszerű vagy tematikus név, évszám teszteket.
![adatbázis modell](_sources/Historia/historia.jpg)

## Sportverseny

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

## Film
Csapattagok: Molnár Krisztián, Hajdu István, Polyák Alex János
![adatbázis modell](_sources/Film/film.jpg)

## Kölcsönzés
Csapattagok: Oláh Péter, Nagy Ferenc
![adatbázis modell](_sources/Kolcsonzes/kolcsonzes.jpg)


