# b618reboot
#### About
Simple Python script for rebooting Huawei B618 LTE router via web interface.

My router occasionally drops the LTE connection (whilst still responding on the LAN interface) and the quick fix is to reboot the device using its web interface. Which was ok for a while, but as I was going on holiday and wanted to keep thr LTE connection running to have access to the security camera, I decided to quickly write a script which I could run from cron on my home Linux server to trigger the reboot when the connection goes down. 

It is not pretty (sorry!) but it does the job for me. It might work with other Huawei router using SCRAM authentication but do not have any around, so cannot test. Feel free to let me know if it does.
Happy to accept improvements via pull requests!

#### Model and firmware info
Device name: B618s-22d

Hardware version: WL1B610FM

Software version: 11.185.01.01.104

Web UI version: 21.100.26.00.0


