# viSee
viSee platform

Run:  
1. Turn on Raspberry Pi 

2. Connect Ethernet

3. Run DHCP Server

4. Go to Downloads/stream-video-browser/stream-video-browser

5. python webstreaming.py --ip 0.0.0.0 --port 8000 (Server is running on http://127.0.0.1:8000/)

6. Turn on Mobile Hotspot and connect to WiFi from Raspberry Pi

7. ./ngrok authtoken [Authorization token from ngrok website]

8. ./ngrok http http://127.0.0.1:8000
