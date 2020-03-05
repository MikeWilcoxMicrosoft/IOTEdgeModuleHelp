Two screen shots on how to update an environment variable for your 'running' Azure IOT Edge Module.

Note, in these screen shots we modify the IP of the 'webstream' module so that it matches the VisionAI Kit camera's DHCP assigned IP address. 

!![image](https://user-images.githubusercontent.com/57420850/75941830-51c0a700-5e56-11ea-9316-c50d0a656e29.png)

Now verify that the environment variable has been changed, see screen shot: 

![image](https://user-images.githubusercontent.com/57420850/75941860-6c931b80-5e56-11ea-9041-23eeb2d39084.png)

Note, the module ( container ) on the IOT Edge Device will restart and read in the new 'environment variable' setting(s) changed. 

Enjoy. 
