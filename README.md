# YouTubeRSS

Flux RSS statique des dernières vidéos YouTube de [Thomas Hammoudi](https://www.youtube.com/@ThomasHammoudi), régénéré tous les 2 mois par n8n (workflow `t6SBAQu7IVevc4Dh`).

URL servie par GitHub Pages : <https://thomashmd.github.io/YouTubeRSS/feed.xml>

Consommé par Metricool pour planifier automatiquement les posts Facebook / Bluesky / Threads associés à chaque vidéo. Remplace l'ancien webhook n8n `https://n8n.thomashammoudi.com/webhook/video-youtube` (déprécié).

## Pourquoi statique ?

Metricool appelait l'ancien webhook avec une fréquence très élevée, ce qui polluait les logs n8n et chargeait inutilement Railway. Un fichier statique sur GitHub Pages est gratuit, rapide, et n'a aucune limite de débit.

Même approche que le repo voisin [`ChineurRSS`](https://github.com/ThomasHMD/ChineurRSS).
