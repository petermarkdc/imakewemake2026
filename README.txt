ESP32-CAM Robot Lab - self-hosted copy
=======================================

1. Copy "Demo Video.mp4" from the kit folder (Tutorial Video > Demo Video)
   into the media/ folder and rename it to: demo-video.mp4
   (No video yet? Open index.html, find "videos:" near the bottom and change it to: videos: [])

2. Upload this whole folder to a static host (Netlify, Cloudflare Pages, GitHub Pages, or your own web server).
   index.html must be at the top level of the site.

3. Point your domain at the host (see the host's "custom domain" page; usually a CNAME DNS record).

Notes
- Open it through the web address, not by double-clicking index.html: the kit-code download needs a web server.
- Code highlighting, zip downloads and Save-as-PDF load small libraries from cdnjs.cloudflare.com, so students need internet.
