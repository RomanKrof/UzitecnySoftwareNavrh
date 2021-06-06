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
    * Pro uživatele programu - managery, sekretářky
  * Ostatní dokumenty
    * https://github.com/RomanKrof/UzitecnySoftwareKrof.git (Záměr)
* Scénáře
  * Všechny reálné způsoby použití
    * Program bude možné použít jako deník nebo zápisník pro schůzky a konference uživatele
  * Typy uživatelských rolí, „personas“
    * Manageři, sekretářky, někdo, kdo není sběhlý v IT - začátečníci
  * Vymezení rozsahu – co v programu **NEbude**
    * Program nebude obsahovat kalendář, který by zobrazoval všechny schůzky
  * Na co se **NEbude** klást důraz
    * Nebude se klást důraz na rychlost zápisu schůzek
* Celková hrubá architektura
  * Pracovní tok
    * Uživatel zapne program
    * Vybere si jednu ze záložek, které reprezentují typy schůzek - pracovní nebo soukromá
    * Uživatel přidá do vybraného seznamu schůzku
    * Uživatel přepne seznam a upraví dříve přidanou položku
    * Uživatel uloží změny a program vypne
  * Všechny detaily: obrazovky, okna, tisky, chybové zprávy, logování
    * Hlavní okno, které v levé části obrazovky bude zobrazovat list schůzek s vybranou záložkou (2 - pracovní a soukromé schůzky), ve spodní části bude tlačitko k přidání, v pravé části budou vypsány všechny podrobnosti dané schůzky, v pravém spodním rohu části s podrobnostmi bude tlačítko, které uloží všechny úpravy, v levém spodním rohu části s podrobnostmi bude tlačítko na úpravu vybrané schůzky
    * https://github.com/RomanKrof/UzitecnySoftwareNavrh/blob/main/N%C3%A1vrh%20hlavn%C3%ADho%20okna.png
    * Při kliknutí na tlačítko úpravy se vyvolá menší podokno, ve kterém budou vypsány podrobnosti, které se budou moci přepsat, ve spodní části tohoto podokna bude tlačítko pro uložení změn schůzky, při chybném zadání informací se u dané informace objeví červeně zbarvený text s chybovou hláškou
