# Návrh Save & Meet
## Verze 1

Roman Krof <br/>
krof.roman.2018@skola.ssps.cz <br/>
23. 5. 2021

* Úvod
  * Účel dokumentu
    * Dokument slouží k rychlému představení programu
  * Konvence dokumentu
    * Všechny kritické požadavky budou tučně
  * Pro koho je dokument určený
    * Pro uživatele programu - managery, sekretářky, někdo, kdo není sběhlý v IT - začátečníci
  * Ostatní dokumenty
    * https://github.com/RomanKrof/UzitecnySoftwareKrof.git (Záměr)
* Scénáře
  * Všechny reálné způsoby použití
    * Program bude možné použít jako deník nebo zápisník pro schůzky a konference uživatele
  * Typy uživatelských rolí, „personas“
    * Každý uživatel, který program použije, bude moci číst, upravovat, vytvářet a mazat data uložená na konkrétním zařízení
  * Vymezení rozsahu – co v programu **NEbude**
    * Program nebude obsahovat kalendář
  * Na co se **NEbude** klást důraz
    * Nebude se klást důraz na rychlost zápisu schůzek
* Celková hrubá architektura
  * Pracovní tok
    * Uživatel zapne program, zapíše novou pracovní schůzku, upraví soukromou, uloží seznamy a program vypne
  * Všechny detaily: obrazovky, okna, tisky, chybové zprávy, logování
    * Program bude jedno okno na obrazovce, k úpravě informací vyskočí menší podokno, při chybě vyskočí jiné podokno, bude potřeba pouze klávesnice a myš s monitorem
