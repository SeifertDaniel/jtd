---
title: Datenbank bereinigen
parent: Deinstallation
nav_order: 5
---

# Datenbank bereinigen 

Das Modul legt Informationen in der Datenbank ab. Sofern diese Daten nicht mehr benötigt werden, können diese gelöscht werden. 

> [!] Legen Sie sich vorab bitte unbedingt eine Sicherung an, um die Daten im Zweifelsfall wiederherstellen zu können.
    
Für das Modul **{{ site.modulename }}** sind dies die folgende Tabellen und Felder:

* die komplette Tabelle `d3order2ordermanager`
    
und diese Felder in bestehenden Tabellen:

* in Tabelle `d3modprofile`:  
  * das Feld `D3_OM_EXECMANUALLY`
  * das Feld `D3_OM_MARKORDER`
  * das Feld `D3_OM_ORDERSAVETRIGGERED`
  * das Feld `D3_OM_ORDERFINISHTRIGGERED`
  
sowie diese Einträge in bestehenden Tabellen:

* in Tabelle `d3_cfg_mod`:  
  * den Eintrag `oxmodid = "{$modcfgident}"` **)

**) Diesen Eintrag gibt es ggf. für jeden Subshop. Entfernen Sie diesen nur für die Mandanten, in denen das Modul **nicht** mehr installiert ist. 
