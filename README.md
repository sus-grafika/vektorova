# Vektorová grafika

- **vektor** 
	- vektor lze reprezentovat uspořádanou množinou souřadnic, píšeme ```v=[1,2,3]```, kde x-ová souřadnice vektoru je 1, y-ová souřadnice vektoru je 2, ...
	- vektor může mít libovolný počet souřadnic, počtu souřadnic říkáme dimenze
- **vektorová funkce**
	- vektorová funkce je funkce, která příjmá nějaký vstup a jako výstup vrací vektor
	- jednoduchým příkladem by byla vektorová funkce ```f(x) = [x, x^2]```, která příjmá parametr x a vrací uspořádanou dvojici - bod v rovině
	- pokud bychom touto funkcí zobrazili všechny body nějakého intervalu, např ```(-1,1)``` a zakreslili výstup funkce do roviny, získáme křivku (konkrétně část paraboly)
	- křivky v rovině tedy můžeme popsat vektorovou funkcí, které lze reprezentovat v počítači
- **křivka**
	- křivka ve 2D je nějaká množina bodů z roviny. Z každýho bodu křivky musejí vézt jen 2 směry "dopředu" a "dozadu". Správná definice je složitější
	- my jsme schopný je v počítači reprezentovat vektorovými funkcemi
	- například kružnice se dá reprezentovat funkcí ```f(x)=[cos(x),sin(x)]``` případně ještě rovnicí s druhejma mocninama známou z geometrie 
	- existují i speciální popisy křivek (ne křivky! fakt jen jejich popisy) se kterejma se dobře pracuje, jsou složitě matematicky odvozený atd
		- polynomiální křivky
		- spline křivky
		- beziérovy křivky
		- ...
- souřadné systémy (nadstavba)
	- souřadnej systém klasickej je kartézskej, známej ze střední školy
	- ta myšlenka, že se na křivce dá pohybovat jen dvěma směrama se pak dá rozvést, že souřadnici bodu na křivce bude tvořit buď dvojice bodů a nebo ten parametr t.
	- na vysoké škole se daj tyhlo lokální souřadnice vyjádřit i parciálníma derivacema, ale to už je hodně nadstavba...
- **Plocha** ve 2D
	- Plocha je nějaká množina bodů ohraničená křivkou. Plochu/oblast můžeme tedy reprezentovat křivkou a výplní dané plochy
- **renderování**
	- renderování je nutnou součástí vektorová grafiky, jelikož vektorovou grafiku jako takovou nelze na počítači zobrazit, jsou to jen funkce a jejich parametry. Displeje obecně umí pracovat pouze s rastrem - mřížkou pixelu - displej je jen mřížka pixelů
	- způsobů renderování je mnoho a všechny jsou složitý, jedná se o látku vysoké školy
	- je ale důležitý o tom vědět, je to nedílná součást vektorový grafiky, bez renderování by to byly jen nějaký funkce který neumíme zobrazit
- **výhody**
	- pro některé (křivkami dobře popsatelné) objekty platí, že budou ve vektorovém formátu zabírat málo místa (stačí málo křivek -> málo informací v souboru)
	- matematický popis je nekonečně přesný, vektorový obrázek můžeme tedy vyrenderovat nekonečně přesně (a tedy zoomnout libovolně blízko "bez ztráty kvality")
	- i po uložení do souboru lze s vektorovými funkcemi opět manipulovat ve editoru který to podporuje
- **nevýhody**
	- udělat vektorový obrázek je složitější než vyfotit fotku, člověk to musí dělat ručně
	- nelze na nich zachycovat fotky a jiné objekty s nekonečnými detaily, slouží pouze pro jednodušší objekty
- **využití**
	- v architektuře na návrh domů apod
	- schémata, ilustrace, grafy
	- loga, vizitky, grafika
	- tlačítka v prohlížeči/operačním systému, fonty, ...
- **praxe**
	- inkscape, illustrator, correl, affinity
	- soubory svg, pdf, ai (adobe illustrator picovinka)



