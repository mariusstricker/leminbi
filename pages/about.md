---
layout: page
title: Virtuelle Ausstellung
permalink: /about/
---

Leminbi ist ein Fantasiename, angelehnt an [Lemmings](https://en.wikipedia.org/wiki/Lemmings_(video_game)), ein Videogame aus den 1990er Jahren. Was aber haben pixelige Wuselkreaturen mit Pflanzendias zu tun? Gar nichts. Doch wenn bedacht wird, dass der *Erbauer* dieser Website keine Ahnung von den wirklichen Rechenkapazitäten und -geschwindigkeiten eines Computers hatte und dann beginnt mit einem Terminal zu arbeiten, wird diese Verbindung möglicherweise etwas verständlicher. Denn ein Befehl reicht, zum Beispiel *git -push*, und abertausende Arbeitsschritte werden in beinahe Lichtgeschwindigkeit ausfgeführt, akkurat protokolliert im Terminal und unmöglich für die menschliche Wahrnehmung, auch nur ansatzweise mitlesen zu können. Und dies kann im Grunde nichts anderes bedeuten, als dass die Lemmings überhaupt nicht unter der Erde leben und sich dort abrackern, sondern ihr Zuhause müssen ganz eindeutig die Computer dieser Welt sein. Sie sind die wahren Götter der Nullen und Einsen. Und wäre ich ein König, ich würde sie zu Leminbis schlagen! 


**Glasdias**

Die Pflanzenbilder in dieser Ausstellung sind Digitalisate aus der Sammlung [Historische Glasdias](https://sammlungen.pestalozzianum.ch/gd-196-1) der Stiftung Pestalozzianum in Zürich, das einen Bestand von über 15'000 Glasdias hat. Über die Provenienz der physischen Objekte konnte bei Nachforschungen durch das Pestalozzianum nichts in Erfahrung gebracht werden. Deshalb bleibt auch ungeklärt, auf welche Person die Initialen *I.H.* verweisen, die auf einigen Dias ersichtlich sind. Der Entstehungszeitraum wird auf 1925 bis 1950 geschätzt. Die meisten Dias des Pestalozzianums sind monochromatisch, im Unterschied zu den polychromen Pflanzendias. Allerdings, und das macht nebst der Mehrfarbigkeit den besonderen Reiz der Pflanzendias aus, wurden sie handkoloriert. Bei den Dias mit dem [Gestreiften Seidelbast](https://mariusstricker.github.io/leminbi/arumacula/obj16/), dem [Gamander-Ehrenpreis](https://mariusstricker.github.io/leminbi/arumacula/obj14/) oder dem [Duftveilchen](https://mariusstricker.github.io/leminbi/arumacula/obj3/) ist dies besonders anschaulich. Die Vermutung steht im Raum, dass die Dias einst von einem Fotogeschäft hergestellt wurden, entweder als Auftragsarbeit oder aber für das eigene Archiv, das damals eine ähnliche Funktion gehabt haben dürfte wie heutige Bilddatenbanken (Keystone, Getty Images usw.). Das Pestalozzianum jedenfalls erwarb diese Glasdias zu einem nicht bekannten Zeitpunkt, stellte thematische Sammlungen zusammen und verlieh diese für den Anschauungsunterricht an Schulen.


**IIIF**

Die Digitalisate wurden in einem ersten Schritt von .tif nach .jpg konvertiert und anschliessend nach dem IIIF-Standard aufbereitet. IIIF steht für [International Image Interoperability Framework](https://iiif.io/) und ermöglicht, wie der Name sagt, die Interoperabilität zwischen Servern, Websites und Applikationen für den Transfer digitaler Bilder. Oder anders gesagt: Anstatt ein Bild hundertfach zu kopieren und zu speichern, wird ein IIIF-Bild einmal auf einem Server, zusammen mit einem IIIF-Manifest, dem Herzstück des Frameworks, hochaufgelöst hinterlegt. Über verschiedene API im Manifest können IIIF-Bilder über Image Viewer ([Mirador](https://projectmirador.org/), [OpenSeadragon](https://openseadragon.github.io/) usw.) in beliebige Websites oder Apps eingebunden werden. Zudem können sie individuell annotiert, skaliert und zugeschnitten werden. Das Framework ist stark *community driven* und verkörpert gewissermassen den Grundgedanken von Open Science. Grundlage dafür sind offene Nachnutzungslizenzen für digitale Objekte wie [Creative Commons](https://creativecommons.org/).  


**GitHub**
Die Aufbereitung der IIIF-konformen Glasdias erfolgte mit [Annonatate](https://annonatate.herokuapp.com/profile/?tab=status) und dem Workflow [Wax](https://github.com/minicomp/wax/) von [Minicomp](https://github.com/minicomp). Alle Files zu dieser Ausstellung sind auf GitHub im [Leminbi-Repository](https://github.com/mariusstricker/leminbi) zugänglich (s. auch Realisation).


**Lizenzen**

Alle Elemente dieser Website sind nachnutzbar, für Bilder und Websiteinhalte gilt [CC-BY](https://creativecommons.org/licenses/by/4.0/deed.en) (Creative Commons Attribution 4.0 International), für den verwendeten Wax-Workflow die [MIT-Lizenz](https://github.com/minicomp/wax/blob/main/LICENSE.txt) und das Git-Repository die [GNU Public General Public License v2.0](https://de.wikipedia.org/wiki/GNU_General_Public_License).
