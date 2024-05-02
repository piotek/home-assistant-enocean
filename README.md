# Home Assistant EnOcean
Versuch einer besseren Dokumentation zum Einsatz des Systems EnOcean auf der Home Assistant Plattform

# Einleitung 
Die doch immer wieder großen Verständnisprobleme bei der Integration von EnOcean Komponenten und  Systemen in die Home Assistant Welt, haben zur Veranlassung geführt, zu diesem Thema eine hoffentliche einfachere Darstellung des Themas zu finden und allen Interessierten näher zu bringen.

# Kurzerläuterung zum System EnOcean
Das EnOcean System und dessen Entstehung ist weitreichend bekannt und ausreichend im Internet dokumentiert. Hauptziel war die Entwicklung von extrem stromsparenden Sensoriken. Heute gibt es durch die offene Darstellung des EnOcean Protokolls eine große Vielzahl solcher Sensoren, aber auch Aktoren, von den unterschiedlichsten Herstellern. Alle arbeiten mit dem EnOcean Funkprotokoll, welches sehr kompakt aufgebaut ist (wenig Daten) und dadurch sehr gut für eine schnelle Kommunikation ist. 
EnOcean ist heute eines der wenigen Systeme welches noch eine direkte Kommunikation zwischen 2 Komponenten ermöglicht - ohne das eine Zentrale oder ein Gateway notwendig wäre. EnOcean steht damit also dem NoCloud Gedanken des Home Assistant Systems sehr nahe. Heute sind also kaum noch Systeme zu finden, mit denen z.B. eine Hausflur Lichtseuerung mittels eines Bewegungsmelders und einem Licht Aktor ohne jegliche Zentralen realsierbar ist. Vorteil ist also die rein lokal (ohne Internet) mögliche Haussteuerung. 
Natürlich ist die Einbindung von EnOcean Komponenten auch in Zentralen via Gateways möglich, so dass auch dieses System "Smart" werden kann. Beachtet man aber die loklaen Fähigkeiten des Systems, erkennt man recht schnell, dass Hausautomationen mit EnOcean sehr nachhaltig und sicher sein können, denn eine Abhängigkeit vom Internet ist nicht gegeben.
Die Firma Eltako als einer der großen Komponentenhersteller für das EnOcean System hat neben dem Funk gebundenen EnOcean Komponenten auch ein EnOcean Bus System für den Schaltschrank entwickelt. Heute kann man dieses System in vielen Häusern einiger Haushersteller als Basissystem finden. Das aktuelle "14er Bus System" hat auch einen "12er" Vorgänger. Hauptmerkmal des 14er Bussystems ist eine drahtgebundene Verbindung aller Komponenten auf einer Hutschiene. Auf dieser Verbindung wird das offene EnOcean EEP2 Protokoll "gesprochen". Zusätzlich besiztz dieses System Komponenten die zum einem den Bus verwalten und zum anderen mit Enocean Funkkomponenten ausserhalb des Busses "reden" können (FAM14).     

# Anschluss an Smart Home Zentralen





