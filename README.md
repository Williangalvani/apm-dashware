# apm-dashware
Collection of scripts for getting APM flight logs to play nice with Dashware

## Usage
```bash
sdlog2_dump.py your_flight_log.bin -e -f your_flight_log.csv -m GPS -m ATT -m NTUN -m CTUN -m MODE -m CURR -m RSSI
```

Use the files under DashWare to set up new Dashware data profiles, new customs datatypes and templates.
Copy the 3 folders inside DashWare folder to dashware dataprofiles directory on your computer, usually is located in "C:\Users\YourUsername\Documents\DashWare\"
Open Dashware and select APM Copter - Template to start working on ArduPilot's converted log.

TODO: much better documentation
