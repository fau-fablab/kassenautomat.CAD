# kassenautomat.CAD
Konstruktionspläne für den Kassenautomat

## Komponenten aus CAD:
Automatengehäuse aus Holz (12mm Multiplex, Scharniere)



Technische Zeichnungen:

* Gehäuse Zusammenstellung
  * Gehäuse Holzkasten
  * Tür oben
  * Tür unten
  * Schub oben Zusammenstellung
    * Schubboden oben
    * Haltewinkel Münzwechsler
    * Haltewinkel Geldscheinleserzubehör
 * Schubboden unten


## Elektronische/Elektromechanische Komponenten:


* NV11 Geldscheinleser
* MEI CashFlow 7900 Münzwechsler
* Money Controls Compact Hopper SBB (square bowl base)
* 24V Netzteil TODO (2A ohne Hopper, 5A??? für Hopper+Münzwechsler)
* PC-Netzteil
* Mini-ITX Mainboard
* Festplatte



## Mechanische Komponenten

* Schubladenschiene: 2 * http://www.teleskopschienen24.de/teleskopschienen/vollauszuegebis35kg/ IN 300mm!!

* 2x RJ45 Durchgang Neutrik NE8FDP oder kompatibel (gibts auch in schwarz): www.thomann.de/de/neutrik_ne8fdp.htm

* Kastenschloss BASI KS500 ohne Sperrbügel http://www.basi-gmbh.de/cms/fileadmin/Datenbl%C3%A4tter/1301-0005-KS%20500%20ohne%20Sperrb%C3%BCgel%20silber%20mit%20AS.pdf

*  Metrische Kabelverschraubungen (TODO welche Größe) für Strom etc., z.B. Reichelt MBFK12 + MGM12


*  70mm	 30.530.303	Winkelstahl, blank, scharfkantig	30/30/3mm 
*  140mm	30.302.002	Flachstahl,blank unleg.DIN1652		20/2mm
*  Schlosschrauben M5x30 ca 20 Stück Hornbach 1,50€

## Legende Farben im CAD

* dunkelrot Zugang (man muss hinkommen können)
* dunkelgrau Kühlung (Luftstrom benötigt)
* blau Platz für Kabel
* hellgrau: Front Geldscheinleser
* grün Münzgeld Aus-/Eingang

## TODO im CAD

* non-CAD-Fertigungszeichnungen aus Netdrive kopieren
* Patrick: Hopper-Details und neuer Hopperdeckel
* Nicht mehr eingebundene Teile löschen, z.B. alte Version des Münzeinwurfs
* Zeichnungen als PDF erzeugen und erneuern
* Netzteil statt Trafo einzeichnen, Befestigung Netzteil
* nutzlose Münzausgabeklappe entfernen


## Abhängigkeiten

Beim Umkonstruieren muss u.A. folgendes getestet werden:


* Gehäuse (oben) passend zu Frontblech, Münzeinwurf
* Münzeinwurf, Frontblech, Ausschnitt im Gehäuse, Führung mittig zum Münzwechsler
* SchubOben-Boden
* Münzausgang: passend zu Hopper Münzwechsler
* Platzierung Cashbox zu Münzwechsler
* Münzeinwurf darf nicht mit Gehäuse kollidieren! -> Querschnitt anschauen
* Cashbox-Entnehmbarkeit
* Kollision Münzer-Mainboard?
* Schubladen rein/raus, Tür auf/zu kollisionsfrei möglich?


## NICHT IM CAD enthalten


Kabelausgang PC-Netzteil - oder Netzteil durch ein eins kleineres ersetzen

Befestigung Bondrucker, Barcodeleser, FAUCardleser-Befestigungsklotz, etc.

kleinere Holzschrauben

Befestigung der Münzausgabe am SchubUnten (Durchgangslöcher anzeichnen und bohren)