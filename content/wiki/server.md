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
### DHCP Server (optional)
Wie im Netzwerkartikel beschrieben kann ein DHCP Server nötig, wenn ein User sich nicht selbst eine IP-Adresse zuweisen muss. Ein DHCP Server findet sich meistens im Server, kann aber auch auf Windows und Linux Maschinen eingerichtet werden
### DNS Server (notwendig, jedoch nicht on-prem notwendig)
Computer kommunizieren miteinander über das TCP/IP Protokoll, sprich jeder PC im Netzwerk hat eine IP-Adresse. Nun stelle man sich vor, wenn man Google aufrufen möchte, müsste man sich die IP-Adresse von Google merken, das wäre einfach nur mühselig sich jede IP-Adresse zu merken. Also tippt man im Browser www.google.de ein. Mit dieser Information kann aber der Computer nichts anfangen, diese Adresse muss als erstes in eine IP-Adresse umgewandelt werden. Genau darum kümmert sich ein DNS Server, dieser übersetzt die Adresse die du suchst in eine IP-Adresse.
