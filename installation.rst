Installation
============

Wir liefern das Modul :productname:`GDPR Opt-in` 3.0 standardmäßig mit OXID eShop 7.0 aus.

Bei einer normalen Installation müssen Sie das Modul also nicht installieren, sondern können direkt mit dem Konfigurieren loslegen.

Abhängig von Ihrer Installation des OXID eShops können Sie das Modul jedoch bei Bedarf manuell nachinstallieren.

|prerequisites|

Sie haben OXID eShop Version 7.x.

|procedure|

1. Laden Sie das Modul :productname:`GDPR Opt-in` aus dem Repository herunter und installieren Sie es.

   Führen Sie dazu im Hauptverzeichnis des Shops (in dem die Datei :file:`composer.json` liegt) einen der folgenden Befehle aus:

   * Um die die letzte für den OXID eShop (Compilation) 7.0.0 und höher veröffentlichte Version des Moduls zu installieren:

     .. code:: bash

        composer require --update-no-dev oxid-esales/gdpr-optin-module:^3.0.0

   * Um die aktuelle und noch nicht veröffentlichte Version des Moduls zu installieren:

     .. code:: bash

        composer require --update-no-dev oxid-esales/gdpr-optin-module:dev-b-7.0.x

2. Um das Modul zu aktivieren, tun Sie Folgendes:

   a. Wählen Sie :menuselection:`Erweiterungen --> Module`.
   b. Wählen Sie das Modul.
   c. Wählen Sie auf der Registerkarte :guilabel:`Stamm` des Moduls die Schaltfläche :guilabel:`Aktivieren`.

3. Um temporäre Dateien zu löschen, löschen Sie aus dem Verzeichnis :file:`/tmp` des Shops alle Dateien und Ordner außer der Datei :file:`.htaccess`.



.. Intern: oxdajh, Status: