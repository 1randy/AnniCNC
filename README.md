# AnniCNC

![AN000001 AnniCNC komplett thumbnail](img/AN000001%20AnniCNC%20komplett_tn.png)
 
 
:warning: **Use at your own risk - work in progress**

## Einleitung


In diesem Repo stelle ich meine Plaene und Designs der "AnniCNC" Portalfraese der Community zur Verfuegung.
Viele Ideen der Umsetzung habe ich mir von anderen Selbstbauten und den Foren geholt, danke daher (unter 
anderem und nicht ganz vollstaendig) an:


- Youtube: [UnclePhil](https://www.youtube.com/c/UnclePhil) - [EndCNC](https://www.youtube.com/c/SebastianEnd) - [Talla83](https://www.youtube.com/user/talla83) - [AlexCNC](https://www.youtube.com/c/AlexCNC) - [RotarySMPC](https://www.youtube.com/c/RotarySMP)
- Foren: [CNC Werk](https://cncwerk.de/forum/) - [CNC Ecke](https://www.cncecke.de/forum/forum.php)
- Discord: ["CNC, Späne und Chaos"](https://discord.gg/AsD3zVaeg5) - ["Spanbrecher"](https://discord.gg/Vr6PEbVU)


<p><br>


## Dokumente

Die Dokumente sind einheitlich nach dem Schema XXXX Kategorie/Bauabschnitt/Bauteile + YYYY = Nr. benannt.

Ordnerstruktur:

`dxf/`: Dateien fuer Selbstfertigung der Fraesteile<br>
`stl/`: Dateien fuer Selbstfertigung der 3D Druckteile<br>
`pdf/`: Übersichts- und Explosionszeichnung im Order<br>
`img/`: Bilder und Ansichten<br>
`misc/mesa`: Angepasstes mesa Bitfiles fuer den Betrieb von LinuxCNC<br>

### AN00 Baugruppen komplett

	TBD 0001 Fraese komplett
	TBD 0002 Rahmen montiert
	TBD 0003 Rahmen mit Stirnseiten montiert
	TBD 0004 Rahmen mit Portal montiert

	0011 Stirnseite Vorne montiert
	TBD 0021 Stirnseite Hinten montiert
	TBD 0031 Portal komplett (Seiten + Platte)
	TBD 0033 Portal Motorhalter
	0041 Portal Platte montiert
	TBD 0051 Z Achse montiert

### AN01 Baugruppen Explosionszeichnungen

	TBD 0001 Rahmen
	0011 Stirnseite Vorne
	TBD 0021 Stirnseite Hinten
	TBD 0031 Portal links
	TBD 0032 Portal rechts
	TBD 0033 Portal Motorhalter
	0041 Portal Platte
	TBD 0051 Z Achse

### AN02 Fraesteile

	0001 Stirnplatte Vorne
	0002 Stirnplatte Hinten
	0003 Stirnplatte Lagerhalter
	0004 Stirnplatte Motorhalter

	0011 Portalwange links
	     Rev01 - Verbreiterung untere Kante + Passstifte
	0012 Portalwange rechts
	     Rev01 - Verbreiterung untere Kante + Passstifte
	0013 Portalwange Lagerhalter
	0014 Portalwange Motorhalter
	0015 Portalwange Motorplatte

	0021 Portal Platte
	0022 Portal Block Adapter

	0031 Z-Achse Platte
	     Rev01 - Verlaengerung auf 380mm, Sackloecher fuer M6 schrauben
	     Rev02 - Zusaetzliche Befestigungen fuer Z-Achse Bremse, Halter Energiekette
	0032 Z-Achse Block Adapter
	0033 Z-Achse Spindelplatte
	     285 mm & 350mm Länge
	0034 Z-Achse Motorplatte
	0035 Z-Achse Motorhalter
	     Rev01 - zusaetzliche M5 fuer Riemenspanner

### AN03 Druckteile

	0001 Riemenspanner 25mm
	0002 Riemenspanner 35mm
	0003 Kabelschlepp Halter schmal
	0004 Kabelschlepp Halter breit
	0005 Kabelschlepp Halter gewinkelt
	0006 Kabelschlepp Fuehrung
	0007 Anschlussplatte Steuerung

	0011 Sensorhalter Achsen
	0012 Sensorhalter Portal
	0013 Magnethalter kurz
	0014 Magnethalter lang
	0015 Radiatorhalter
	0016 Spindlehalterung 80mm

### AN04 elektrische teile (motoren, spindel, schalter)

TBD

### AN05 mechanische teile (muttern, winkel alu, lager, zahnriemen, kugelumlauf)

TBD


## Disclaimer

This work is private and licensed by [CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/)<p>




