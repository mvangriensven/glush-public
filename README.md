# Glush

http://glush.cyberise.nl/

Glush is a device tracking and DDNS tool that monitors the uptime of devices, server's and nodes supporting Dynamic DNS domains.
As of right now, Glush is in a public alpha testing phase in which the reliability of our service will be tested under pressuring circumstances to ensure availability.
Glush is free to use up to 5 devices and 5 nodes, with subscriptions and an easily accessible Dynamic DNS Service to be introduced in the future.

## Installing Glush

As of right now, Glush is only supported on Windows, but will soon be available on Linux as well.

- Download the Glush Client, and store the .exe file in a persistent path
- Copy the .exe file, and paste it as shortcut in the following path: C:\Users\%user%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
  - Please ensure to change the %user% in the given path to the name of your current user account
- Right-click on your created shortcut and open 'Properties'
- In the target path, after the " " containing the path of the .exe file, add the following parameters:
  - --apikey=your-accounts-apikey
  - --devicename=My Device
  
- Once complete, please make sure to manually launch Glush with the created shortcut for the first time to ensure the parameters have been configured properly and also troubleshoot any potential conflicts with an antivirus.

## Roadmap
- ~~Setting up a simple but usable front-end~~
- ~~Setting up a demo client which communicates to our API~~
- Reworking front-end to support all current and future needs
- Building the Glush Client for Linux
  - Improving the ease of installing Glush
- Implementing additional features
  - Displaying an up-time graph and percentage indicator.
  - Displaying device statistics
    - CPU type & manufacturer
      - Average CPU load
    - amount of RAM and set up
      - Average RAM usage
    - Hard disk storage
 - Shift Glush into a public beta testing phase!
