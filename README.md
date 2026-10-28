# IPTV TV — app Fire TV / Android TV

Lecteur IPTV (playlist M3U, navigation télécommande, favoris) emballé en APK.
La page web se trouve dans `app/src/main/assets/iptv-tv.html` — pour mettre l'app à jour,
remplace ce fichier et pousse sur GitHub : l'APK se reconstruit tout seul.

## Obtenir l'APK (sans Android Studio)
1. Crée un dépôt GitHub (ex. `iptv-tv`) et pousse ce dossier dessus (branche `main`).
2. Onglet **Actions** → le workflow « Build APK » tourne (~3 min).
3. L'APK est dans **Releases** (à droite sur la page du dépôt) → `IPTV-TV.apk`.

## Installer sur le Fire TV Stick
1. Sur le stick : Réglages → Mon Fire TV → Options pour les développeurs
   → **Applications de sources inconnues** : activer pour « Downloader ».
   (Si « Options pour les développeurs » est caché : Réglages → Mon Fire TV → À propos
   → clique 7 fois sur le nom de l'appareil.)
2. Installe l'app **Downloader** depuis l'Appstore Amazon.
3. Dans Downloader, tape l'URL de l'APK (page Releases → clic droit sur `IPTV-TV.apk` → copier le lien),
   ou l'URL courte raccourcie. Installe.
4. L'app « IPTV TV » apparaît dans Applications. Ouvre-la, entre ton URL de playlist.

## Télécommande
- Liste : flèches / OK
- Lecteur : ▲▼ chaîne, OK infos, ◀ favori, ▶ muet, Retour → liste
