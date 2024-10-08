---
title: Shopanpassungen installieren
parent: Update
nav_order: 5
---

# Shopanpassungen installieren

### **im Adminbereich**

Ob Shopanpassungen notwendig sind, ist von der Versionsänderung des Moduls abhängig.
  
Möglicherweise sehen Sie nach dem Neuaktivieren des Moduls den Installationsassistent, der Sie durch die Änderungen führt. Folgen Sie dann den einzelnen Schritten. Möchten Sie die Änderungen manuell installieren, können Sie sich über diesen Assistenten ebenfalls eine Checkliste erstellen.
 
Wird der Assistent nicht gezeigt (Sie sehen wieder die Modulübersicht), waren keine Anpassungen am Shop notwendig.
  
Ob erforderliche Updates ausgeführt werden sollen, können Sie jederzeit im Adminbereich unter [ (D3) Module ] -> [ Modul-Connector ] -> [ Modulverwaltung ] -> [ Modulinstallation ] prüfen.

### **oder auf der Kommandozeile**

Der Installationsassistent steht Ihnen ebenfalls auf der Kommandozeile (CLI) zur Verfügung. Führen Sie diesen Befehl im Hauptverzeichnis Ihres Shops (oberhalb des `source`- und `vendor`-Verzeichnisses) aus:

```bash
./vendor/bin/d3modules_install
```