## Firefox browser with RDP server with audio

Usage

```bash
docker run -d --shm-size 1g -p 3389:3389 --name firefox danielguerra/firefox-rdp
```
*note --shm-size 1g is needed for firefox 

Then connect with your RDP client to the container and use firefox