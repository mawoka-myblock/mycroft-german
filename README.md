# Mycroft.conf Deutsch mit IBM

Dies ist die Mycroft.conf, damit Mycroft mit euch auf deutsch redet und euch versteht! Ich benutze IBM aals Spracheingabe, da es kostenlos ist und ich IBM mehr vertraue als Wit.ai (Facebook)! Als Sprachausgabe benutze ich espeak welches lokal auf dem Computer läuft!


# Espeak Installation

- Einfach `sudo apt install espeak espeak-data mbrola mbrola-de6` eingeben und los gehts!
- Am Raspberry Pi könnt ihr mbrola nicht über die Paketverwaltung installieren. Da müsst ihr folgendes eingeben: `wget http://steinerdatenbank.de/software/mbrola3.0.1h_armhf.deb && sudo dpkg -i mbrola3.0.1h_armhf.deb` Nun könnt ihr den Rest einfach installieren: `sudo apt install espeak espeak-data mbrola-de6` Und jetzt sprichtMycroft nach einem Neustart auch Deutsch!



# Speicherort

- Gebt folgendes in die Konsole ein: 
`mycroft-config edit user`
  wenn das nicht funktioniert , einfach die Datei selber mit einem Texteditor bearbeiten!
- Die Datei ist bei ~/.mycroft/mycroft.conf (/home/BENUTZERNAME/.mycroft/mycroft.conf)

# Skills
Wenn ihr deutscheSkills für Mycroft sucht, besucht mal den Entwickler [Gras64](https://github.com/gras64)! Alle offiziellen Skills, die ihr im [Marketplace](https://market.mycroft.ai/skills) findet, sind auch deutsch!


## Pandora (Freiwillig)
Pandora ist ein kostenloser Musikstreamingdienst aus den USA, der nur in den USA verfügbar ist!
**Aber** das ist ja kein Problem! Erstellt euch einfach einen Account auf Protonvpn.com und installiert euch das Tool für Linux auf dem Computer wo Mycroft läuft: ``sudo apt install -y openvpn dialog python3-pip python3-setuptools`` und ``sudo pip3 install protonvpn-cli`` Jetzt müsst ihr es nur noch einrichten: `sudo protonvpn init` dort gebt ihr **Nicht** eure Protonvpn-Anmeldedaten sondern die Anmeldedaten von [HIER](https://account.protonvpn.com/account#openvpn). Wenn das erfolgreich war, gebt ihr `sudo protonvpn c US-FREE#2` ein und wartet. Nun hat euer Ferät eine Amerikanische IP-Adresse und ihr könnt Pandora einrichten und installieren. Vorher müsst ihr euch aber noch ein Account erstellen. Das macht ihr am besten auch mit Protonvpn. Da müsst ihr selber mal gucken wie ihr das macht!

