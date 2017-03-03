# xrypto-siegen

Folien und Organisatorisches für Crypto-Parties in Siegen.

## Submodule und Themenübersicht:
* handbook: Das berühmte Crypto-Party Handbuch (englisch).

* [xrypto-auth](https://github.com/xrypto-siegen/xrypto-auth): Authentisierung
  * sichere Passwörter
  * Wie oft ändern?
  * Merkregeln
  * Passwort-Tabellen
  * Passwort-Manager (keepassx, pass / Pass4Win)
  * 2-Faktor Authentisierung
  * im Browser: auf HTTPS achten! (evtl. live-Demo)

* [xrypto-mail](https://github.com/xrypto-siegen/xrypto-mail): e-mails
  * PGP (Thunderbird+Enigmail)
  * S/MIME
  * Transportverschlüsselung mit (START)TLS
  * live-Demo: fake-mails verschicken

* [xrypto-chat](https://github.com/xrypto-siegen/xrypto-chat): instant messaging
  * Crypto-Messenger
  * OTR
  * Sprachverschlüsselung

* [xrypto-phon](https://github.com/xrypto-siegen/xrypto-phon): Smartphones
  * Lock screen
  * Berechtigunen (privacy guard)
  * WLAN-Sicherheit (evtl. live-Demo: Spoofing)

* [xrypto-bank](https://github.com/xrypto-siegen/xrypto-bank): Onlinebanking
  * Methoden zur TAN-Generierung
  * TAN-Eingangsdaten kontrollieren!

* [xrypto-anon](https://github.com/xrypto-siegen/xrypto-anon): Anonymität
  * TAILS / Tor browser bundle
  * Firefox-Plugins
  * Cookies, Tracker

* [xrypto-data](https://github.com/xrypto-siegen/xrypto-data): Datenverschlüsselung
  * Grundlagen: Verschlüsselungsverfahren
  * Datenverschlüsselung mit GnuPG
  * Container (VeraCrypt)
  * Festplattenverschlüsselung (VeraCrypt, LUKS)

* [xrypto-file](https://github.com/xrypto-siegen/xrypto-file): File-Sharing
  * ownCloud / nextCloud
  * e-mails
  * Retro-Share?
  * Tox?

## Verwaltung der Submodule:
Mit dem folgenden Befehl können automatisch alle Submodule geklont werden:
```
git clone --recursive git@github.com:xrypto-siegen/xrypto-siegen.git
```

Alle Submodule auf den aktuellen Stand bringen:
```
git submodule update
```
