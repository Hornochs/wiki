Author: Gamienator

+++
title = "Server"
+++

Der Begriff ist sehr weitläufig, ein Server kann eigentlich so jeder Rechner sein des es gibt. Es muss nicht so ein großer Schrank sein, der Hochleistungsaufgaben erledigt. Ziel und Zweck eines Server ist es einen Dienst bereitzustellen. Welche Dienste für eine LAN notwendig ist, muss jede Veranstaltung für sich selbst entscheiden.

## Begriffserklärungen
### On-Premise (On-Prem)
Dieses beschreibt einen Server, Dienst oder was auch immer, der sich lokal in deiner Örtlichkeit verbindet. Dein Router zuhause z. B. ist On-Prem
### Cloudlösung
Das Gegenteil von On-Premise, Cloud Dienste sind nur aus dem Internet erreichbar, die du meistens auch nicht selber verwalten musst, dieses wird über eine monatliche Gebühr über einen Dienstleister erledigt.

## Infrasruktur
### DHCP Server (Optional)
Wie im Netzwerkartikel beschrieben kann ein DHCP Server nötig, wenn ein User sich nicht selbst eine IP-Adresse zuweisen muss. Ein DHCP Server findet sich meistens im Server, kann aber auch auf Windows und Linux Maschinen eingerichtet werden
### DNS Server (Notwendig, jedoch nicht on-Prem notwendig)
Computer kommunizieren miteinander über das TCP/IP Protokoll, sprich jeder PC im Netzwerk hat eine IP-Adresse. Nun stelle man sich vor, wenn man Google aufrufen möchte, müsste man sich die IP-Adresse von Google merken, das wäre einfach nur mühselig sich jede IP-Adresse zu merken. Also tippt man im Browser www.google.de ein. Mit dieser Information kann aber der Computer nichts anfangen, diese Adresse muss als erstes in eine IP-Adresse umgewandelt werden. Genau darum kümmert sich ein DNS Server, dieser übersetzt die Adresse die du suchst in eine IP-Adresse. DNS Server können sowohl von Windows, Linux als auch online genutzt werden. Ein On-Prem DNS Server gibt einem die Möglichkeit eigene DNS-Einträge zu erstellen.

### Intranet (Empfohlen ab 20 User, Pflicht ab 50 User , muss nicht lokal gehostet werden)
Größere LANs können um eine Verwaltung nicht herum, meistens geschieht dies durch eine Website um Useranmeldungen, Turniere, Catering usw. aus einer Hand managen zu können. In [diesem Git Repository](https://github.com/LANparties/awesome-lanparty-software#lan-party-management) könnt ihr unter LAN-Party-Management eine Auflistung gängiger Systeme finden. Bei LANs die eine schwache Internetleitung haben, oder mehr als 50 Teilnehmer haben sollten den Service lokal hosten, um lange Ladezeiten zu vermeiden.

## Gameserver
Was am Anfang durch mangelnde Rechenleistung notwendig war, wird heute immer mehr obsolet: Dedizierte Spieleserver. Auch in diesem Punkt ist es vollkommen euch überlassen, ob ihr sowas braucht oder nicht. Wenn ihr aber eine LAN organisiert und Turniere abhalten wollt, ist es sehr zu empfehlen eigene Spieleserver aufzusetzen, soweit es das Spiel zulässt. Beliebte Spiele die heute immer noch eigene Dedicated Server anbieten sind:

 - Counter-Strike (jegliche Version, auch Global Offensive)
 - Call of Duty 1, 2, 4, Modern Warfare 3
 - Trackmania Nations
 - Unreal Tournament (alle Versionen)
 - Minecraft (Java Edition)

Eine empfehlenswerte Seite ist [Linux Game Server Managers](https://linuxgsm.com). Dort kann man ziemlich einfach einen Dedicated Server auf einer Linux Maschine bauen, mit zusätzlichen Funktionen wie Telegram Alert, Discord Alert uvm. Unter [Servers](https://linuxgsm.com/servers/) kann man auch sehen, welche Spiele von LinuxGSM unterstützt werden. 
