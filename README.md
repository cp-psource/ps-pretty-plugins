# PS-Pretty Plugins

Verleihe Deinen Plugin-Seiten in Multisite-Netzwerken das Aussehen eines App Stores mit ausgewählten Bildern, Kategorien und einer erstaunlichen Suche.

## Mit Pretty Plugins können Sie Plugins in Kategorien gruppieren, ihnen auffällige Funktionsbilder geben und sie in einem benutzerfreundlichen Raster anzeigen.

Machen Sie das Finden und Installieren von Plugins zum Kinderspiel. Pretty Plugins ist ein unverzichtbares Tool für jeden Netzwerkbesitzer. Es bietet eine zentrale Steuerung und Konfiguration der Plugins-Seite jeder Website. Kombinieren Sie es mit [Pro Sites](http://premium.wpmudev.org/project/pro-sites/ „Lesen Sie mehr über das Pro Sites-Plugin“), um einen fantastischen kostenpflichtigen Plugin-Shop zu erstellen.

Große Symbole und ein vertrautes Rasterlayout sorgen für ein optisch weitaus ansprechenderes Layout im Vergleich zum standardmäßigen Basiseintrag.

![Screengrab der Plugins-Seite mit dem Rasterlayout](http://premium.wpmudev.org/wp-content/uploads/2013/11/prettyplugins-ss12.jpg)

  Große Symbole und ein Rasterlayout machen das Entdecken von Plugins zum Kinderspiel

  Plugins können in mehrere Kategorien gruppiert werden, die vom Netzwerkadministrator definiert werden, was es Websitebesitzern erleichtert, neue Funktionen zu entdecken und zu installieren.

![Screengrab der Plugin-Kategorien](http://premium.wpmudev.org/wp-content/uploads/2013/11/prettyplugins-ss2.jpg)

  Gruppieren Sie Plugins in Kategorien, um sie leichter finden zu können

  Eine umfassende Einstellungsseite ermöglicht es einem Netzwerkbesitzer, alle Aspekte der Plugins-Seite zu verwalten, einschließlich Titel, Untertitel, Bilder und die Sichtbarkeit von Beschreibungen. Die Einstellungen können sogar exportiert und importiert werden!

![Screengrab der Einstellungsseite](http://premium.wpmudev.org/wp-content/uploads/2013/11/prettyplugins-ss11.jpg)

  Konfigurieren Sie alle Aspekte des Verhaltens und Aussehens der Plugins-Seite

  Für jedes Plugin wird eine genauere Steuerung bereitgestellt. Als Netzwerkadministrator können Sie den Plugin-Namen, den Link und die Beschreibung überschreiben – Sie können das Plugin beliebig vielen vorhandenen Kategorien zuweisen oder neue erstellen – und Sie können ein vorgestelltes Bild laden.

![Screengrab der Plugin-Details-Bearbeitungsfunktion](http://premium.wpmudev.org/wp-content/uploads/2013/11/prettyplugins-ss41.jpg)

  Überschreiben Sie alle Plugin-Attribute

  Pretty Plugins gibt Ihnen eine beispiellose Kontrolle über das Aussehen und Verhalten der Plugins-Seite und macht es für Websitebesitzer einfacher denn je, ihre Plugins selbst zu verwalten und neue Funktionen zu finden und zu ihrer Website hinzuzufügen.

## Verwendung

### Für den Anfang

Lesen Sie zunächst den Abschnitt [Plugins installieren](../wpmu-manual/installing-regular-plugins-on-wpmu/) in unserem umfassenden [WordPress- und WordPress-Multisite-Handbuch](https://premium.wpmudev.org/manuals/) ), wenn Sie neu bei WordPress sind. Beachten Sie, dass dieses Plugin nur für Multisite-Installationen konzipiert ist und nicht auf einzelnen Sites funktioniert.

### Konfigurieren der Einstellungen

Nach der Installation und Aktivierung sehen Sie in Ihrem Menü „Netzwerkeinstellungen“ einen neuen Menüpunkt: Pretty Plugins. Klicken Sie jetzt auf den Menüpunkt Pretty Plugins.

![pretty-plugins-1000-menu](https://premium.wpmudev.org/wp-content/uploads/2013/11/pretty-plugins-1000-menu.png)

  Die Einstellungen sind recht einfach. Aber lassen Sie uns sie trotzdem durchgehen, ja? 

![1\. Setup-Modus aktivieren/deaktivieren. 2\. Wählen Sie Ihr bevorzugtes Thema. 3\. Wählen Sie das Ziel des Plugin-Links aus. 4\. Wählen Sie Ihre Screenshot-Einstellungen aus. 5\. Plugin-Beschreibungen ein-/ausblenden. 6\. Passen Sie die Beschriftungen an.](https://premium.wpmudev.org/wp-content/uploads/2013/11/pretty-plugins-1000-settings.png)

  1\. Setup-Modus aktivieren/deaktivieren.
2\. Wählen Sie Ihr bevorzugtes Thema.
3\. Wählen Sie das Ziel des Plugin-Links aus.
4\. Wählen Sie Ihre Screenshot-Einstellungen aus.
5\. Plugin-Beschreibungen ein-/ausblenden.
6\. Passen Sie die Etiketten an.

  1\. Wahrscheinlich möchten Sie _Setup-Modus aktivieren_ auf „True“ gesetzt lassen, während Sie die Dinge konfigurieren.

* Wenn der Setup-Modus aktiviert ist, können Sie beim Aufrufen der Hauptseite nur eine Vorschau anzeigen. Die Unterseiten sind davon nicht betroffen.
* Sobald Sie fertig und mit Ihrer Konfiguration zufrieden sind, setzen Sie sie auf „False“, um Ihre neue Pretty Plugins-Seite auf allen Unterseiten in Ihrem Netzwerk zu aktivieren.

2\. _Theme für Plugin-Seite auswählen_ ist genau das: Sie können das Theme auswählen, das zur Anzeige der verfügbaren Plugins auf allen Unterseiten verwendet wird.

* Derzeit ist in diesem Plugin ein Theme enthalten: QuickSand.
* Um Ihr eigenes benutzerdefiniertes Theme zu erstellen, kopieren Sie einfach das QuickSand-Theme in /pretty-plugins/themes/ und benennen Sie es um. Anschließend können Sie das Layout und das Stylesheet bearbeiten und Ihr benutzerdefiniertes Design in Ihren Ordner /wp-content/uploads/prettyplugins/themes/ hochladen. Es steht dann zur Auswahl zur Verfügung.

3\. Um auszuwählen, wohin der Plugin-Link verweist, haben Sie vier Möglichkeiten:

* _Plugin-Original-URL_ verweist auf die URL, die der Plugin-Autor in das Plugin eingefügt hat.
* _Benutzerdefinierte Plugin-URL_ verweist auf die URLs, die Sie für jedes Plugin festgelegt haben (wir werden weiter unten darauf eingehen).
* _Benutzerdefinierte URL des Plugins oder, falls keine benutzerdefinierte URL vorhanden ist, Original-URL_ bietet Ihnen das Beste aus beidem: Wenn Sie keine benutzerdefinierte URL für ein Plugin eingeben, wird als Link standardmäßig die URL verwendet, die der Autor des Plugins eingefügt hat.
* _Disable_ deaktiviert effektiv alle Plugin-Links.

4\. Hier wählen wir aus, welche Screenshots für Plugins verwendet und angezeigt werden sollen.

* Wenn „True“ eingestellt ist, verwendet _Ersten Screenshot automatisch laden_ den ersten verfügbaren Screenshot im Plugin-Ordner. Dadurch wird Pretty Plugins angewiesen, nach einer Datei namens _screenshot-1.png_ zu suchen. Wenn diese Datei nicht in einem Plugin-Ordner vorhanden ist, wird für dieses Plugin nichts angezeigt.
* Wenn auf True gesetzt, weist _Screenshot automatisch mit korrektem Namen laden_ Pretty Plugins an, in Ihrem Ordner /wp-content/upload/prettyplugins/screenshots/ nach Dateien zu suchen, die _Sie_ dort mit den richtigen Namen hochgeladen haben.
     * Wenn sich das Plugin beispielsweise unter _wp-content/plugins/akismet/akismet.php_ befindet, sollte der Screenshot-Name _akismet-akismet.png_ lauten. Beachten Sie, dass mit dieser Methode nur PNG-Bilder funktionieren.

5\. Sie können _Minimize Descriptions_ auf True setzen, um nur Screenshots auf Unterseiten-Plugin-Seiten anzuzeigen. Dadurch wird die Anzeige eines Links aktiviert, auf den Ihre Benutzer klicken können, um die Beschreibung umzuschalten, wenn sie weitere Informationen über das Plugin wünschen. 6\. Mit den Einstellungen „Beschriftungen für Plugin-Seite verwalten“ können Sie anpassen, wie Plugins den Benutzern Ihrer Unterseite angezeigt werden.

* _Plugin-Seitentitel_ ändert den Namen des Menüelements und den Seitenanfangstitel auf der Plugin-Seite. Möglicherweise bevorzugen Sie beispielsweise das Wort „Addons“.
* _Plugin-Seitenbeschreibung_ ist der benutzerdefinierte beschreibende Text, der direkt unter dem Titel der Plugin-Seite angezeigt wird.
* _Benutzerdefiniertes Link-Label_ ist das, worauf Benutzer klicken, um die Plugin-URL zu besuchen, die Sie oben unter _Wählen Sie aus, wohin der Plugin-Link verweist_ festgelegt haben. Wenn Sie dies auf „Deaktivieren“ eingestellt haben, wird dies ausgeblendet.

### Zusätzliche Tools

Es werden einige zusätzliche Tools bereitgestellt, mit denen Sie Plugin-Daten und -Einstellungen verwalten können.

![1\. Datei config.xml exportieren/importieren. 2\. Alle Daten löschen.](https://premium.wpmudev.org/wp-content/uploads/2013/11/pretty-plugins-1000-tools.png)

  1\. Datei config.xml exportieren/importieren.
2\. Alle Daten löschen.

  1\. Sie können eine config.xml-Datei _exportieren_, um Ihre Einstellungen auf Ihrem Computer zu sichern, und sie dann in Ihren Ordner /wp-content/uploads/prettyplugins/ _importieren_.
 
  2\. Die _Reset_-Funktion ist praktisch, wenn Sie von vorne beginnen möchten. :) :)

### Plugin-Details bearbeiten

Schauen wir uns nun an, wie Sie anpassen können, wie einzelne Plugins in der Plugin-Liste auf allen Websites angezeigt werden. Gehen Sie in Ihrem Netzwerkadministrator zu Plugins > Installierte Plugins und klicken Sie auf den Link Details bearbeiten für jedes Plugin, das Sie bearbeiten möchten.

![pretty-plugins-1000-edit](https://premium.wpmudev.org/wp-content/uploads/2013/11/pretty-plugins-1000-edit.png)

  Dadurch wird ein vertrauter Bereich geöffnet, der dem Schnellbearbeitungsbereich beim Bearbeiten von Beiträgen ähnelt. Schauen wir uns nun den ersten Teil genauer an.

![pretty-plugins-1000-edit-details](https://premium.wpmudev.org/wp-content/uploads/2013/11/pretty-plugins-1000-edit-details.png)

  Geben Sie einen benutzerdefinierten _Name_ ein, um den Anzeigenamen des Plugins zu ersetzen. Wenn nichts eingegeben wird, wird wie immer der tatsächliche Name des Plugins angezeigt. Sie können eine _benutzerdefinierte URL_ eingeben, um die vom Plugin-Autor angegebene URL zu ersetzen. Beachten Sie, dass diese URL nur verwendet wird, wenn Sie oben unter _Wählen Sie aus, wohin der Plugin-Link zeigt_ eine der benutzerdefinierten URL-Anzeigeoptionen ausgewählt haben. Sie können auch eine benutzerdefinierte _Bild-URL_ hochladen oder darauf verlinken. Dadurch wird das Bild festgelegt, das für dieses Plugin angezeigt wird.

* Zum Hochladen können Sie ein Bild aus Ihrer Medienbibliothek auswählen oder den Namen der Datei eingeben, die Sie in /wp-content/uploads/prettyplugins/screenshots/ hochgeladen haben.
* Wenn Sie lieber auf ein anderswo gehostetes Bild verlinken möchten, geben Sie einfach die URL ein.
* Die empfohlenen Bildabmessungen betragen 600 x 450 Pixel.

Schauen wir uns nun den anderen Teil an.

![pretty-plugins-1000-edit-details-2](https://premium.wpmudev.org/wp-content/uploads/2013/11/pretty-plugins-1000-edit-details-2.png)

  Um _Kategorien_ hinzuzufügen, klicken Sie auf den Link _Neue Kategorie_, geben Sie Ihren Kategorienamen ein und klicken Sie auf _Hinzufügen_. Anschließend können Sie Ihre Kategorie aus der Liste auswählen.

* Sie können für jedes Plugin mehrere Kategorien auswählen, wenn Sie möchten.
* Alle Kategorien, die nicht von Plugins verwendet werden, werden automatisch gelöscht.

Sie können eine benutzerdefinierte _Beschreibung_ eingeben, die die vom Plugin-Autor hinzugefügte Beschreibung ersetzt. Lassen Sie das Feld leer, um stattdessen diese Beschreibung zu verwenden. Wenn Sie mit der Bearbeitung fertig sind und auf die Schaltfläche „Aktualisieren“ geklickt haben, werden Ihre Anpassungen direkt in der Plugin-Liste in Ihrem Netzwerkadministrator angezeigt.

![pretty-plugins-1000-edit-details-3](https://premium.wpmudev.org/wp-content/uploads/2013/11/pretty-plugins-1000-edit-details-3.png)

### Erfahrung als Site-Administrator

Sobald alles konfiguriert ist und Sie „Setup-Modus aktivieren“ in den allgemeinen Einstellungen auf „Falsch“ setzen, sehen Ihre Site-Administratoren etwas, das diesem Bild sehr ähnlich ist.

![pretty-plugins-1000-site-view](https://premium.wpmudev.org/wp-content/uploads/2013/11/pretty-plugins-1000-site-view.png)

  Aktive Plugins werden mit einem grünen Band im Bild angezeigt. In unserem Beispiel haben wir die Beschreibungen so eingestellt, dass sie nicht angezeigt werden, sodass Site-Administratoren sie anzeigen können, indem sie auf den Detaillink klicken. Wenn Sie lieber Ihre eigenen Bilder für die Bänder verwenden möchten, ersetzen Sie einfach die Standardbilder in /pretty-plugins/themes/quick-sand/images/. Wenn Sie Ihr eigenes Design erstellt haben, ersetzen Sie natürlich stattdessen die Designs im Ordner /images/. Oben (und im Plugins-Menü) befinden sich die Filteroptionen. Das sind alle Kategorien, die wir für unsere Plugins eingerichtet haben. Wenn Sie auf einen dieser Links klicken, werden nur Plugins angezeigt, die dieser Kategorie zugeordnet sind.

### PS Bloghosting-Integration

Oh ja, das haben wir! Alle Plugins, die Sie den Ebenen [Pro Sites](https://premium.wpmudev.org/project/pro-sites/ „WordPress Pro Sites Plugin – WPMU DEV“) im Premium-Plugin-Modul hinzugefügt haben, werden auf allen Websites mit angezeigt ein „Pro“-Menüband in der Ecke des Plugin-Bildes („!“). Bewegen Sie Ihren Mauszeiger über ein beliebiges Plugin, das Sie im Premium-Plugin-Modul für Pro Sites-Stufen festgelegt haben, und Sie erhalten die Meldung „Upgrade auf [Stufe]“. Wenn die Site nicht auf die Pro Site-Ebene aktualisiert wurde und der Site-Administrator auf eines dieser Plugins klickt, wird er zu Ihrer Pro Sites-Upgrade-Seite weitergeleitet. Wie cool ist das? Möglicherweise haben Sie im obigen Screenshot auch bemerkt, dass wir Pretty Plugins-Kategorien erstellt haben, die unsere Pro Sites-Stufen widerspiegeln: Free, Premium und Super. Das macht es für Ihre Site-Administratoren einfach zu einfach, auf einen Blick die Vorteile eines Upgrades ihrer Site auf eine kostenpflichtige Pro Sites-Stufe in Ihrem Netzwerk zu erkennen. Gern geschehen. :) Wir hoffen, dass Sie und Ihre Benutzer Pretty Plugins genießen und das Beste daraus machen!