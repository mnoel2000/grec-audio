# grec-audio

Pack audio du module Vocabulaire de l'app **Greek Syllables**.

`voc/` contient les mp3 (mono 24 kHz 32 kbps) pour les 5000 mots les plus fréquents :
- `voc_<rang>.mp3` — mot grec
- `voc_<rang>_fr.mp3` — traduction française
- `voc_<rang>_ex.mp3` — phrase d'exemple en grec

Servis à l'app via le CDN jsDelivr (`https://cdn.jsdelivr.net/gh/<user>/grec-audio@main/voc/...`),
téléchargés une fois puis cachés sur l'appareil (hors-ligne ensuite). NON bundlés dans l'APK.

Généré par `grec-app/data/import-anki.py`.
