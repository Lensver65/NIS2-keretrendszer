# NIS2 megfelelés feladatai Gantt diagram 

```mermaid
gantt
    	title NIS2 HU
    	dateFormat  YYYY-MM-DD
    	section Kockázatmenedzsment keretrendszer felállítása és dokumentálása
    	Kockázatkezelési keretrendszer alkalmazása: KK0, 2024.06.25, 90d

    	section Biztonsági Osztályba Sorolás
    	Biztonsági osztályba sorolás: BO0, after KK6, 30d
 
    	section Védelmi Intézkedések
    	Védelmi intézkedések beazonosítása: VI0, after BO0, 30d

    	section Rendszerbiztonsági Terv Elkészítése
	Rendszerbiztonsági terv elkészítése: RBT0, after VI0, 30d

    	section Védelmi Intézkedések Végrehajtása
    	Védelmi intézkedések végrehajtása: VV0, after RBT0, 60d


    	section Védelmi Intézkedések Értékelése
	Védelmi intézkedések értékelése: VE0, after VV6, 30d

	section Rendszer Használatbavétele
	Rendszer használatbavétele: RH0, after VE6, 30d

	section Folyamatos Felügyelet és Frissítések
	Folyamatos felügyelet és frissítések:milestone, after RH6, 7d
```
