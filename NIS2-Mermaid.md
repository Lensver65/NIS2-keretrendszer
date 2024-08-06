# NIS2 Keretrendszer alkalmazása, feladatok, határidők (relatív kezdődátumokkal)

> Az alábbiakban vagy a jogszabályban meghatározott fix kezdődátummal meghatározott, vagy 2024. augusztus 01-i indulás szerint kerülnek kerültek meghatározásra a Gantt diagrammok. [Egy másik oldalon összesített diagramban](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2%20Gantt.md) található a teljes feladatkör, a jogszabályban meghatározott fix dátumok alapján.
> A lent található Gantt diagramokat kimásolva (a diagram jobb felső sarkában található copy ikonra kattintva), azok kezdő dátumát módosítva bárki személyre tudja szabni magának az ábrát, mely alapján meg tudja határozni az egyes tevékenységekhez szükséges időkereteket.

1. **[Kockázatkezelési keretrendszer alkalmazása](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2-Mermaid.md#kock%C3%A1zatmenedzsment-keretrendszer-fel%C3%A1ll%C3%ADt%C3%A1sa-%C3%A9s-dokument%C3%A1l%C3%A1sa)**

* **Feladat:** Felkészülés a keretrendszer alkalmazására
* **Határidő:** A jogszabály hatályba lépésétől számított 3 hónap
* **Felelős:** Szervezet vezetője

2. **[Biztonsági osztályba sorolás](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2-Mermaid.md#biztons%C3%A1gi-oszt%C3%A1lyba-sorol%C3%A1s)**

* **Feladat:** Az elektronikus információs rendszerek biztonsági osztályba sorolása
* **Határidő:** A kockázatkezelési keretrendszer felállítását követően 1 hónap
* **Felelős:** Kijelölt biztonsági szakértő

3. **[Védelmi intézkedések beazonosítása](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2-Mermaid.md#v%C3%A9delmi-int%C3%A9zked%C3%A9sek)**

* **Feladat:** A biztonsági osztályhoz tartozó védelmi intézkedések azonosítása
* **Határidő:** A biztonsági osztályba sorolást követően 1 hónap
* **Felelős:** Biztonsági csapat

4. **[Rendszerbiztonsági terv elkészítése](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2-Mermaid.md#rendszerbiztons%C3%A1gi-terv-elk%C3%A9sz%C3%ADt%C3%A9se)**

* **Feladat:** A kiválasztott védelmi intézkedések dokumentálása a rendszerbiztonsági tervben
* **Határidő:** A védelmi intézkedések azonosítását követően 1 hónap
* **Felelős:** Biztonsági csapat

5. **[Védelmi intézkedések végrehajtása](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2-Mermaid.md#v%C3%A9delmi-int%C3%A9zked%C3%A9sek-v%C3%A9grehajt%C3%A1sa)**

* **Feladat:** A rendszerbiztonsági tervben dokumentált intézkedések végrehajtása
* **Határidő:** A rendszerbiztonsági terv elkészítését követően 2 hónap
* **Felelős:** IT és biztonsági csapat

6. **[Védelmi intézkedések értékelése](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2-Mermaid.md#v%C3%A9delmi-int%C3%A9zked%C3%A9sek-%C3%A9rt%C3%A9kel%C3%A9se)**

* **Feladat:** A megvalósított védelmi intézkedések értékelése
* **Határidő:** A végrehajtás befejezését követően 1 hónap
* **Felelős:** Kijelölt biztonsági szakértők

7. **[Rendszer használatbavétele](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2-Mermaid.md#rendszer-haszn%C3%A1latbav%C3%A9tele)**

* **Feladat:** Döntés a rendszer használatbavételéről vagy folytatásáról
* **Határidő:** A védelmi intézkedések értékelését követően 1 hónap
* **Felelős:** Szervezet vezetője

8. **[Folyamatos felügyelet és frissítések](https://github.com/Lensver65/NIS2-keretrendszer/blob/main/NIS2-Mermaid.md#folyamatos-fel%C3%BCgyelet-%C3%A9s-friss%C3%ADt%C3%A9sek)**

* **Feladat:** A védelmi intézkedések folyamatos felügyelete és a szükséges frissítések elvégzése
* **Határidő:** Folyamatosan, évente legalább egyszer
* **Felelős:** Biztonsági csapat

```mermaid
gantt
    title NIS2 megfelelés Gantt diagram
    dateFormat  YYYY-MM-DD
    section Feladatok
    Kockázatkezelési keretrendszer alkalmazása :T1, 2024-06-25, 90d
    Biztonsági osztályba sorolás :T2, after T1, 30d
    Védelmi intézkedések beazonosítása :T3, after T2, 30d
    Rendszerbiztonsági terv elkészítése :T4, after T3, 30d
    Védelmi intézkedések végrehajtása :T5, after T4, 60d
    Védelmi intézkedések értékelése :T6, after T5, 30d
    Rendszer használatbavétele :T7, after T6, 30d
    Folyamatos felügyelet és frissítések :T8, after T7, 7d
```

## Kockázatmenedzsment keretrendszer felállítása és dokumentálása

A 7/2024. MK rendelet alapján a Kockázatmenedzsment keretrendszer felállítása és dokumentálása alatti al-feladatok és határidők a következők:

1. **Szerepkörök, felelősségek, feladatok és hatáskörök meghatározása és dokumentálása**

* **Feladat:** Meghatározni és dokumentálni az elektronikus információs rendszerek védelmével kapcsolatos szerepköröket, felelősségeket, feladatokat és hatásköröket.

2. **Kockázatmenedzsment stratégia kidolgozása és dokumentálása**

* **Feladat:** Kidolgozni és dokumentálni a kockázatmenedzsment stratégiát, amely leírja, hogyan azonosítja, értékeli, kezeli és felügyeli a szervezet a biztonsági kockázatokat.

3. **Biztonságfelügyeleti stratégia kidolgozása és dokumentálása**

* **Feladat:** Kidolgozni és dokumentálni a biztonságfelügyeleti stratégiát, amely magában foglalja a védelmi intézkedésekhez kapcsolódó tevékenységek ellenőrzésének gyakoriságát, felügyeletének módszereit és eszközeit.

4. **Üzleti célok, funkciók és folyamatok meghatározása és dokumentálása**

* **Feladat:** Meghatározni és dokumentálni az elektronikus információs rendszerek által támogatandó üzleti célokat, funkciókat és folyamatokat.

5. **Rendszer határainak meghatározása és dokumentálása**

* **Feladat:** Meghatározni és dokumentálni a rendszer szervezeti és technológiai határait, valamint az érintett vagyonelemeket, és az adatköröket.

6. **Felelős személyek kijelölése**

* **Feladat:** Kijelölni a kockázatmenedzsment feladatokért felelős személyeket és dokumentálni a nevüket és felelősségi körüket.

## Biztonsági osztályba sorolás:
A 7/2024. MK rendelet alapján a biztonsági osztályba sorolás alatti al-feladatok a következők:

1. **Kockázatmenedzsment keretrendszer felállítása és dokumentálása:**

* **Feladat:** A keretrendszer alkalmazására való felkészülés, amely magában foglalja az elektronikus információs rendszerek védelmével kapcsolatos szerepkörök, felelősségek, feladatok és hatáskörök meghatározását és dokumentálását .

2. **Hatáselemzés elvégzése:**

* **Feladat:** A szervezet elvégzi az elektronikus információs rendszerek hatáselemzését, amely alapján meghatározza a rendszerek biztonsági osztályát .

3. **Biztonsági osztály meghatározása és dokumentálása:**

* **Feladat:** Az elektronikus információs rendszerek biztonsági osztályba sorolása a hatáselemzés eredményei alapján, majd az eredmények dokumentálása a rendszerbiztonsági tervben .

4. **Biztonsági osztályba sorolási döntés jóváhagyása:**

* **Feladat:** A szervezet vezetője jóváhagyja a biztonsági osztályba sorolási döntést .

5. **Védelmi intézkedések beazonosítása:**

* **Feladat:** A biztonsági osztályhoz tartozó védelmi intézkedések azonosítása a kockázatmenedzsment keretrendszer alapján .

6. **Rendszerbiztonsági terv elkészítése és jóváhagyása:**

* **Feladat:** A rendszerbiztonsági terv elkészítése, amely tartalmazza a biztonsági osztályba sorolás eredményeit és az azonosított védelmi intézkedéseket .


## Védelmi intézkedések

A 7/2024. MK rendelet alapján a védelmi intézkedések feladatának alábbi al-feladatai és határidői a következők:

1. **Védelmi intézkedések azonosítása**
   * **Feladat:** Az elektronikus információs rendszer azon komponenseinek meghatározása, amelyek a védelmi intézkedések által megcélzott biztonsági képességet biztosítják vagy támogatják.

2. **Védelmi intézkedések fokozatos bevezetése**
   * **Feladat:** A védelmi intézkedések fokozatos bevezetése a védendő elektronikus információs rendszerek biztonsági osztályozása alapján.

3. **Dokumentáció és eltérések kezelése**
   * **Feladat:** A védelmi intézkedések dokumentálása, beleértve az egyedi eltérések okait és mértékét, valamint azok megfelelőségének és hatékonyságának felülvizsgálata.

4. **Helyettesítő védelmi intézkedések alkalmazása**
   * **Feladat:** Azon esetekben, amikor az adott biztonsági osztályhoz tartozó védelmi intézkedés nem alkalmazható, egyenértékű vagy összemérhető védelmet nyújtó helyettesítő intézkedések alkalmazása.

5. **Biztonsági követelmények meghatározása**
   * **Feladat:** Az elektronikus információs rendszerekre értelmezendő és alkalmazandó biztonsági követelmények megállapítása, a kockázatelemzés alapján testre szabva.

6. **Rendszerbiztonsági terv frissítése**
   * **Feladat:** A védelmi intézkedések tényleges megvalósítása és a tervtől való eltérések alapján a rendszerbiztonsági terv frissítése.

## Rendszerbiztonsági terv elkészítése

A 7/2024. MK rendelet alapján a rendszerbiztonsági terv elkészítése során a következő al-feladatok és határidők szerepelnek:

1. **A rendszer felépítésének és elemeinek meghatározása és dokumentálása**
   * **Feladat:** Meghatározni és dokumentálni az elektronikus információs rendszer (EIR) felépítését és elemeit.

2. **Az EIR hatókörének és alapfeladatainak meghatározása és dokumentálása**
   * **Feladat:** Az EIR hatókörének, alapfeladatainak és biztosítandó szolgáltatásainak dokumentálása az üzleti folyamatok szempontjából.

3. **Szerepkörök és felelősségek meghatározása és dokumentálása**
   * **Feladat:** Azonosítani és dokumentálni az EIR-hez kapcsolódó szerepköröket és felelősségeket betöltő személyeket.

4. **Az EIR által feldolgozott, tárolt és továbbított információtípusok meghatározása**
   * **Feladat:** Dokumentálni az EIR által kezelt adatköröket és azok életciklusát.

5. **Az EIR biztonsági osztályának meghatározása és dokumentálása**
   * **Feladat:** Az EIR biztonsági osztályának meghatározása és alátámasztása megfelelő módon.

6. **Az EIR működési környezetének és kapcsolódó rendszerelemek meghatározása**
   * **Feladat:** Az EIR működési környezetének és a kapcsolódó vagy függő rendszerelemek meghatározása és dokumentálása.

7. **A rendszerre vonatkozó biztonsági követelmények dokumentálása**
   * **Feladat:** Dokumentálni a rendszerre vonatkozó biztonsági követelményeket, beleértve a szükséges védelmi intézkedéseket.

8. **A rendszerbiztonsági terv jóváhagyása és megismertetése**
   * **Feladat:** Gondoskodni arról, hogy a rendszerbiztonsági tervet a meghatározott személyek és szerepkörök megismerjék, és a felelős vezetők jóváhagyják a tervet.

## Védelmi intézkedések végrehajtása

A 7/2024. MK rendelet alapján a védelmi intézkedések végrehajtásához kapcsolódó al-feladatok és határidők a következők:

1. **Védelmi intézkedések azonosítása**
   - **Feladat:** Az elektronikus információs rendszer azon komponenseinek meghatározása, amelyek a védelmi intézkedések által megcélzott biztonsági képességet biztosítják vagy támogatják.

2. **Kockázatelemzés és intézkedési terv készítése**
   - **Feladat:** Kockázatelemzés végrehajtása, majd az eredmények alapján az intézkedési terv elkészítése.

3. **Védelmi intézkedések bevezetésének megtervezése**
   - **Feladat:** A védelmi intézkedések bevezetésének részletes tervezése, beleértve a szükséges erőforrásokat és ütemtervet.

4. **Védelmi intézkedések bevezetése**
   - **Feladat:** A tervezett védelmi intézkedések végrehajtása a meghatározott ütemterv szerint.

5. **Dokumentáció és jelentéstétel**
   - **Feladat:** A végrehajtott védelmi intézkedések dokumentálása és jelentések készítése az eredményekről.

6. **Értékelés és visszacsatolás**
   * **Feladat:** A végrehajtott védelmi intézkedések értékelése és a visszacsatolás beépítése a rendszerbiztonsági tervbe.

## Védelmi intézkedések értékelése

A 7/2024. MK rendelet alapján a védelmi intézkedések értékelése során az alábbi al-feladatok és határidők szerepelnek:

1. **Értékelési terv kidolgozása**
   - **Feladat:** Az értékelési terv kidolgozása, amely leírja az értékelés hatókörét, beleértve az értékelendő védelmi intézkedéseket, azok kiterjesztését és továbbfejlesztését.

2. **Értékelő csoport kiválasztása**
   - **Feladat:** Az értékelési tervnek megfelelő értékelő csoport vagy független értékelők kiválasztása.

3. **Biztonsági értékelés végrehajtása**
   - **Feladat:** A meghatározott biztonsági értékelési módszerek és eszközök alkalmazása, beleértve a mélységi monitorozást, automatizált biztonsági teszteket, sérülékenységszkennelést, rosszhiszemű felhasználói teszteket, stb.

4. **Értékelési eredmények dokumentálása**
   - **Feladat:** Az értékelési eredmények dokumentálása és jelentés készítése, amely összefoglalja az értékelés eredményeit, beleértve az azonosított kockázatokat és javasolt intézkedéseket.

5. **Értékelési eredmények felülvizsgálata és jóváhagyása**
   - **Feladat:** Az értékelési eredmények felülvizsgálata és jóváhagyása a szervezet vezetői által.

6. **Visszacsatolás és rendszerbiztonsági terv frissítése**
   * **Feladat:** Az értékelési eredmények alapján szükséges visszacsatolás biztosítása és a rendszerbiztonsági terv frissítése.

## Rendszer használatbavétele

A 7/2024. MK rendelet alapján a rendszer használatbavételéhez kapcsolódó al-feladatok és határidők a következők:

1. **Használatbavételi terv kidolgozása**
   - **Feladat:** Kidolgozni egy részletes tervet a rendszer használatbavételére, beleértve az összes szükséges lépést és felelősségeket.

2. **Jóváhagyások beszerzése**
   - **Feladat:** A használatbavételi terv jóváhagyása a szervezet vezetése és a biztonsági szakértők által.

3. **Preprodukciós tesztek végrehajtása**
   - **Feladat:** A rendszer preprodukciós környezetben történő tesztelése, hogy biztosítsák a rendszer megfelelőségét és a védelmi intézkedések hatékonyságát.

4. **Visszajelzések gyűjtése és értékelése**
   - **Feladat:** A tesztek eredményeinek összegyűjtése és értékelése, valamint az esetleges szükséges módosítások bevezetése.

5. **Végleges rendszerbiztonsági terv elkészítése**
   - **Feladat:** A végleges rendszerbiztonsági terv elkészítése, amely tartalmazza az összes jóváhagyott és végrehajtott védelmi intézkedést.

6. **Üzembe helyezés**
   - **Feladat:** A rendszer éles üzembe helyezése a végleges terv alapján.

7. **Folyamatos monitorozás és visszacsatolás**
   - **Feladat:** A rendszer folyamatos monitorozása és az esetleges visszacsatolások alapján történő folyamatos javítás.

## Folyamatos felügyelet és frissítések

A 7/2024. MK rendelet alapján a folyamatos felügyelet és frissítések alatti al-feladatok és határidők a következők:

1. **Folyamatos monitorozás és elemzés**
   - **Feladat:** Az elektronikus információs rendszer (EIR) folyamatos monitorozása, beleértve a biztonsági események valós idejű elemzését automatizált eszközök segítségével.

2. **Hibajavítás és frissítések telepítése**
   - **Feladat:** A hibajavítások és biztonsági frissítések rendszeres telepítése, beleértve a szoftver- és firmware-frissítéseket.

3. **Rendszeres sérülékenység vizsgálat**
   - **Feladat:** Rendszeres sérülékenységvizsgálatok végrehajtása, beleértve az automatizált sérülékenységelemzést és a kockázatok értékelését.

4. **Adatbiztonság és integritás ellenőrzése**
   - **Feladat:** Az EIR által kezelt adatok biztonságának és integritásának rendszeres ellenőrzése.

5. **Biztonsági mentések és visszaállítások**
   - **Feladat:** Rendszeres biztonsági mentések készítése és a visszaállítási eljárások tesztelése.

6. **Kockázatmenedzsment folyamatok felülvizsgálata**
   - **Feladat:** A kockázatmenedzsment folyamatok és eljárások rendszeres felülvizsgálata és frissítése a változó körülményeknek megfelelően.

