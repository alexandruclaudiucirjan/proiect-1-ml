1. Clasificare sau regresie? Ce greșeală ar costa mai mult?

Este o problemă de clasificare, deoarece vrem să prezicem dacă un client pleacă sau rămâne. O greșeală importantă este să prezicem că un client rămâne, deși acesta va pleca, deoarece firma pierde ocazia de a încerca să îl păstreze.

2. De ce împărțim datele înainte de scalare?

Împărțim datele în set de antrenare și set de testare înainte de scalare pentru a evita folosirea informațiilor din testare în procesul de învățare. Astfel, evaluarea modelului este mai corectă, deoarece scalarea se învață doar din datele de antrenare.

3. Ce scor are un model care nu știe nimic?

Modelul baseline prezice mereu clasa cea mai frecventă, adică faptul că un client rămâne. Acesta poate avea o acuratețe destul de mare, dar nu identifică deloc clienții care pleacă, deci are recall și F1 egale cu 0 pentru clasa „Pleacă”.

4. Care model a ieșit mai bine și de ce crezi?

Regresia Logistică a obținut rezultate mai bune decât Random Forest. Cred că acest model a reușit să învețe mai bine relația dintre date și plecarea clienților. De aceea, l-aș alege pentru acest proiect.

5. De ce ai ales metrica principală?

Am ales scorul F1 deoarece ține cont atât de precizie, cât și de recall. În acest proiect este important să identificăm clienții care ar putea pleca, fără să ignorăm prea multe cazuri importante.

6. Concluzie: ce model recomanzi, cât bate baseline-ul, o limitare.

Recomand Regresia Logistică, deoarece a obținut rezultate mai bune decât Random Forest în testele realizate. Față de baseline, modelul trebuie să obțină un scor mai bun pentru a demonstra că face predicții utile. O limitare este că rezultatele depind de datele folosite pentru antrenare și pot fi diferite pentru alți clienți.
