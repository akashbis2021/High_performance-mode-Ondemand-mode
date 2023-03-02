# High_performance-mode-Ondemand-mode for LINUX
In this repository I create High-performance-mode / Ondemand mode  for every Linux desktop and server's

#How to set up 
 1. make a folder in /home/username/performance
 2. copy both modes in /home/username/performance
 
#How to setup High-performance mode && Ondemand-mode service
 
 CAUTION:---
 ** copy any one service from two service's (High / Ondemand), which you want to create a service
    that run's automatically at the booting time **
 
 just copy that service in /etc/systemd/system/   

 for example:
  1. sudo cp /home/username/Download/Highper.service  /etc/systemd/system
  2. sudo cp /home/username/Downloas/Ondemand.service /etc/systemd/system
 
 # How to Start service:
  
  1. sudo service highper start
  2. sudo systemctl enable highper.service   
  
  OR if you want to start Ondemandper.service
  
  1. sudo service ondemandper start
  2. sudo systemctl enable ondemandper.service
   
