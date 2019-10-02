Funktionsbeschreibung
=====================

Die Funktionen, die das Modul GDPR Opt-in bereitstellt, können im Frontend des Shops genutzt werden. Sie fordern von Kunden die ausdrückliche Zustimmung zur Speicherung und Verarbeitung ihrer Daten beim Ändern der Rechnungsadresse, dem Anlegen von Lieferadressen, bei der Registrierung im Shop, bei der Bewertung von Artikeln und beim Abschicken von Anfragen über das Kontaktformular.

Die Opt-ins werden erst angezeigt, wenn der Kunde am Shop angemeldet ist. Einzige Ausnahme davon ist die Registrierung.

Rechnungsadresse
----------------
Unter :menuselection:`Mein Konto -> Rechnungs- und Liefereinstellungen` können die Rechnungsadresse sowie alle vorhandenen Lieferadressen eines Kunden eingesehen und bearbeitet werden.

Wurde die Moduleinstellung :guilabel:`Opt-in für Rechnungsadresse anzeigen` aktiviert, muss der Kunde explizit zustimmen, wenn er die Rechnungsadresse geändert hat und diese speichern will. Das Kontrollkästchen für das Opt-in muss dafür angehakt werden.

.. image:: media/screenshots/oxdajj01.png
   :alt: Rechnungsadresse ändern
   :height: 818
   :width: 642

-----------------------------------------------------------------------------------------

Lieferadressen
--------------
Unter :menuselection:`Mein Konto -> Rechnungs- und Liefereinstellungen` werden alle vorhandenen Lieferadressen eines Kunden aufgelistet, wenn das Kontrollkästchen Rechnungsadresse als Lieferadresse verwenden nicht angehakt ist. Hier kann eine vorhandene Lieferadresse bearbeitet oder eine neue hinzugefügt werden.

.. image:: media/screenshots/oxdajj02.png
   :alt: Lieferadresse erstellen oder bearbeiten
   :height: 736
   :width: 644

Wurde die Moduleinstellung :guilabel:`Opt-in für Lieferadresse anzeigen` aktiviert, ist die explizite Zustimmung des Kunden notwendig, damit die Lieferadresse gespeichert werden kann.

Das Bearbeiten und Hinzufügen von Lieferadressen ist auch direkt im Bestellprozess möglich.

-----------------------------------------------------------------------------------------

Registrierung
-------------

Ein Kunde kann sich im Shop registrieren, indem er im Frontend den Link :guilabel:`Anmelden` klickt und dann auf :guilabel:`Registrieren` wechselt. Er kann aber auch im Bestellschritt zwei ein Konto im Shop eröffnen.

Wurde die entsprechende Moduleinstellung aktiviert, kann die Registrierung nur abgeschlossen werden, wenn der dauerhaften Verwendung der im Formular angegebenen Daten für das Kundenkonto explizit zugestimmt wurde.

.. image:: media/screenshots/oxdajj03.png
   :alt: Registrierung
   :height: 296
   :width: 644

-----------------------------------------------------------------------------------------

Bewertung
---------
Kunden können eine Bewertung zu einem Artikel schreiben und für diesen maximal fünf Sterne vergeben. Ist die Moduleinstellung :guilabel:`Opt-in für Artikelbewertungen anzeigen` aktiviert, wird ein Hinweis darauf eingeblendet, dass die Bewertung und der Name des Kunden auf der Detailseite des Artikels angezeigt werden. Ohne die ausdrückliche Zustimmung durch Anhaken des Kontrollkästchens können die Bewertung und das Sterne-Rating nicht gespeichert werden.

.. image:: media/screenshots/oxdajj04.png
   :alt: Artikel bewerten
   :height: 298
   :width: 608


-----------------------------------------------------------------------------------------

Kontaktformular
---------------
Für das Kontaktformular kann festgelegt werden, dass die Daten der Anfrage für deren Beantwortung und für statistische Zwecke verwendet werden. Der Kunde muss den Bedingungen der Verarbeitung seiner Daten explizit zustimmen. Alternativ dazu können auch alle übermittelten Daten direkt nach der Verarbeitung gelöscht werden. Wurde diese Moduleinstellung gewählt, wird dem Kunden ein diesbezüglicher Hinweis angezeigt.

.. image:: media/screenshots/oxdajj05.png
   :alt: Kontaktformular
   :height: 260
   :width: 650


.. Intern: oxdajj, Status: