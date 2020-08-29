# viSee
viSee platform

Run:  
1. Turn on Raspberry Pi 

2. Connect Ethernet

3. Run DHCP Server

4. VNC or PuTTY

## Run all projects with ngrok:
https://dashboard.ngrok.com/get-started/setup
1. Edit ngrok.yml   
    Default configuration file location

    OS X	/Users/example/.ngrok2/ngrok.yml   
    Linux	/home/example/.ngrok2/ngrok.yml   
    Windows	C:\Users\example\.ngrok2\ngrok.yml   

    Example ngrok.yml:   
    viSee/ngrok.yml

2. In folder where is ngrok executable file run:   
    ./ngrok start --all   
    OR   
    ./ngrok start projectname projectname

    projectname - (in ngrok.yml)   
    