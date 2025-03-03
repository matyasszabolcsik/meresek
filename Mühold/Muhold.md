
# MÉRÉSI JEGYZŐKÖNYV   
# Méréstechnikai Feladat: Műhold

**A mérést végző neve:** Szabolcsik Mátyás
**A mérés tárgya:**  Műholdas vételi rendszer kiépítése     
**A mérés száma:** 03. mérés    
**A mérés dátuma:** 2025. 03. 03.    
**A mérést vezette:** Sándor Péter    

**Évfolyam:** 13. E  
**Csoport:** GYAK 1   
**Helyszín:** V3 Labor, kisudvar    

## Feladat célja   
Egy szabadon fogható (FTA) csatorna véletének beállítása, műholdas vételi rendszer kiépítése és vizsgálata, majd optimális vételi jel csatlakoztatása egy set op boxba, amin keresztül képet jelenítünk meg.  

## Felhasznált eszközök   
**Parabolaantenna: D80 Mesh**<br>
**Műholdvevő fej (LNB):Ekselans SATCR LNB**<br>
**Set-top box: Amiko HD 8265+**<br>
**METEK HDD jelmérő**<br>
**Koaxiális kábelek és csatlakozók**<br>
**2-es műholdas jelosztó**<br>
**Szerelési eszközök: iránytű, dőlésszögmérő**<br>

## Feladat menete  
**Első lépésnek összeszereltem az antennát, és rátekertem az LNB fejegységet (Ekselans SATCR).**  
**Internetes műholdvevő adatbázisból (lyngsat.com) kikerestem a(z) FTA csatornákat és választottam egyet, amely az Eutelsat 9B műhold sugároz.**  
**Az iránytű segítségével beállítottam az antenna dőlésszögét, polarizációját pedig a METEK HDD segítségével a lehető legjobb jelre állítottam aminek végül az tetőponti (azimuth) szöge 198 fok lett, emelkedési szöge (elevation) 36 fok és LNB skew (elforgatási) szög 10° lett.**  
**Csatlakoztattam egymással az LNB vevőfejet és a set top boxot, mindezek után csatlakoztattam a set top boxot egy monitorra.**  
**Beállítottam a set top boxon a megfelelő műholdat (Eurobird 9A 9E) és a TP indexet (11958V) és elintítottam egy TP keresést.**  

## METEK HDD képek és jelszintmérés  

<details>
   <summary>Az adás jelerőssége</summary>

   <img src="https://github.com/matyasszabolcsik/meresek/blob/main/its_snapshot_0006.png" Width="600">

</details>

<details>
   <summary>Az adás spektruma</summary>

   <img src="https://github.com/matyasszabolcsik/meresek/blob/main/its_snapshot_0005.png" Width="600">

</details>

<details>
   <summary>A Metek HDD által megjelenített kép</summary>

   <img src="https://github.com/matyasszabolcsik/meresek/blob/main/its_snapshot_0004.png" Width="600">

</details>

<details>
   <summary>A set top boxxal mért erősség és minőség értéke</summary>

   <img src="https://github.com/matyasszabolcsik/meresek/blob/main/IMG_2087.png" Width="600">

</details>