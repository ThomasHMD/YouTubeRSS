**English** | [Français](README.fr.md)

# YouTubeRSS

Static RSS feed of the latest YouTube videos of [Thomas Hammoudi](https://www.youtube.com/@ThomasHammoudi), regenerated every 2 months by n8n (workflow `t6SBAQu7IVevc4Dh`).

URL served by GitHub Pages: <https://thomashmd.github.io/YouTubeRSS/feed.xml>

Consumed by Metricool to automatically schedule the Facebook / Bluesky / Threads posts tied to each video. Replaces the old n8n webhook `https://n8n.thomashammoudi.com/webhook/video-youtube` (deprecated).

## Why static?

Metricool called the old webhook very frequently, which cluttered the n8n logs and needlessly loaded Railway. A static file on GitHub Pages is free, fast, and has no rate limit.

Same approach as the neighboring repo [`ChineurRSS`](https://github.com/ThomasHMD/ChineurRSS).
