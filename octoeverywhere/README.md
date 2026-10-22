# Morley's OctoEverywhere for Home Assistant

# About
[OctoEverywhere](https://octoeverywhere.com/) is an open-source project for remotely controlling and monitoring 3D printers. For Elegoo printers, it requires an external service to act as a bridge between the printer and the OctoEverywhere cloud service. 

This add-on hosts that bridge directly in Home Assistant. I have customized this fork specifically for use with my Elegoo Centauri Carbon 2 (CC2).

# Pre-Requisite
You will need an OctoEverywhere account in order to use their cloud service. If you don't already have one, please use my referral link: https://octoeverywhere.com/?ref=5R5OJL to register.

# Installation

1. Click here to add my repository to your Home Assistant add-ons list:  
  [![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fmorleysprague%2Fhass-addons)

2. Refresh your browser.
3. Find the "Morley's OctoEverywhere" add-on and click the "INSTALL" button.
4. Configure the add-on and click on "START".

# Configuration
Make sure to configure the add-on before starting it. 
Select `elegoo_cc2` as your companion mode, and provide the local IP address of your Elegoo Centauri Carbon 2 (e.g., 192.168.X.X). 

# Connecting to OctoEverywhere
After configuring and starting the add-on, go to the "Log" page of the add-on. If everything went well, you should see a QR code printed there. Scan the code with your phone and log in to your OctoEverywhere account in order to connect this server to your cloud account.
