# Reckon

This repo contains the code for a Raspberry Pi device to use the Resin.io service as a kiosk.  The device will start X window server and run Chromium browser opening the page that you will specify in the environmental variable `URL` on the Resin.io dashboard.

### Configuration
Use Resin.io "Environment Variables" to set an ENV var with URL and use the URL that you want as the default URL. Then click "Show redefines", it might only show up after you've added more devices. Here you can set URL overrides that apply for specific devices.
