# rclone-marco

Startseite und Datenschutzerklärung für den eigenen Google-OAuth-Client, mit dem rclone auf Marcos Google Drive zugreift (Remote `driveA`, Google-Cloud-Projekt `rclone-marco-514216`). Google lässt eine App erst dann aus dem Status „Test“ heraus, wenn beide Adressen auf der Seite „Branding“ eingetragen sind. Im Status „Test“ verfällt jedes Token nach sieben Tagen, deshalb gibt es dieses Repo.

Das Repo ist bewusst **öffentlich**, weil GitHub Pages es ohne bezahlten Plan nur so ausliefert. Es enthält nichts außer den beiden Seiten und keine personenbezogenen Daten.

## Adressen

- Startseite: https://maccu27.github.io/rclone-marco/
- Datenschutzerklärung: https://maccu27.github.io/rclone-marco/datenschutz.html
- Autorisierte Domain in der Console: `maccu27.github.io`

## Betrieb

- Ausgeliefert über GitHub Pages aus `main`, Wurzelverzeichnis. Ein Push auf `main` veröffentlicht die Seiten neu.
- Kein Server, kein Build, kein Railway.
- Werden die Seiten gelöscht oder umbenannt, bleibt die App veröffentlicht, aber Google kann sie bei einer Prüfung beanstanden. Die Adressen in der Console dann mitziehen.
- Die Einstellungen der App liegen in der Google Cloud Console unter Google Auth Platform, Projekt `rclone-marco-514216`.

Angelegt am 11.11.2026 aus dem Projekt `fotos-organisation`.
