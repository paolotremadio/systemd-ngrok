# Installation


Step 1: Place [`ngrok`](https://ngrok.com/download) in `/usr/bin/ngrok`

Step 2: Configure config under `/apps/ngrok.yml`

Step 3: Add `ngrok.service` to `/etc/systemd/system/`

Step 4: Start ngrok service by typing:
```
    systemctl daemon-reload
    systemctl enable ngrok.service
    systemctl start ngrok.service
```
