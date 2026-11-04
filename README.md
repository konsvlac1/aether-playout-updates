# Aether Playout updates

`update.json` describes the latest release of Aether Playout. Every installation reads it twice a day
(Settings → System → Updates) and, when a newer version is out, shows the administrator a ⬆ notice with
what is new and how to update. Updating is always the station's own choice.

Nothing about the station is sent: the request carries only the installed version number.

The file is written and published by the release script (`tools/release.sh`), after the release check
has passed and the image is on Docker Hub.
