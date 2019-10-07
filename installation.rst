Installation
============

Dieses Dokument beschreibt die Installation des Moduls GDPR Opt-in für den OXID eShop (Compilation) 6.0.2 und höher.

.. |schritt| image:: media/icons/schritt.jpg
               :class: no-shadow

Systemvoraussetzungen
---------------------
Für das Modul GDPR Opt-in sind keine speziellen Systemvoraussetzungen notwendig. Es gelten die des OXID eShop: https://docs.oxid-esales.com/eshop/de/6.0/installation/neu-installation/server-und-systemvoraussetzungen.html mit der Einschränkung, dass PHP 5.6 nicht mehr unterstützt wird.

--------------------------------------------------

Neu-Installation
----------------

|schritt| Modul installieren
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Das Modul GDPR Opt-in muss aus dem Repository heruntergeladen und installiert werden. Dazu wird per Konsole eines der folgenden Composer-Kommandos im Hauptverzeichnis des Shops ausgeführt:

.. code:: bash

   composer require oxid-esales/gdpr-optin-module:^2.2.0

Installiert die letzte, für den OXID eShop (Compilation) 6.0.2 und höher veröffentlichte Version des Moduls.

.. code:: bash

   composer require oxid-esales/gdpr-optin-module:dev-master

Installiert die aktuelle und noch nicht veröffentlichte Version des Moduls.

Verwenden Sie den Parameter ``--update-no-dev``, wenn die entwicklungsbezogenen Dateien nicht benötigt werden und nicht am Quellcode gearbeitet wird.

|schritt| Modul aktivieren
^^^^^^^^^^^^^^^^^^^^^^^^^^
Das Modul muss im Shop unter :menuselection:`Erweiterungen --> Module` aktiviert werden. Auf der Registerkarte :guilabel:`Stamm` des Moduls betätigen Sie die Schaltfläche :guilabel:`Aktivieren`.

|schritt| Temporäre Dateien löschen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Löschen Sie alle Dateien und Ordner außer der :file:`.htaccess` aus dem Verzeichnis :file:`/tmp` des Shops.


.. Intern: oxdajh, Status: