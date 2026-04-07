# windows-admin-labs
Document a complete Windows post-installation setup as a technician would for a new workstation deployment. This demonstrates my ability to configure a fresh Windows installation to organizational standards.

#### Document a complete Windows post-installation setup as a technician would for a new workstation deployment. 

#### Tools Used
- Windows 11 VM (NetLab+)
- Snipping Tool
  
# Configure Windows Update

1. Open Settings > Windows Update (left sidebar).
2. Click Advanced options.
3. Under Active hours, set the range to 8:00 AM – 6:00 PM (this prevents restarts during work hours).
![image alt]
5. Toggle Get me up to date to On.
6. Scroll down to Delivery Optimization and click it.
7. Review the setting for Allow downloads from other PCs — this controls whether the PC downloads updates from other devices on the local network (saves bandwidth) or only from Microsoft.
8. Screenshot: Capture the Advanced options page showing active hours and the Delivery Optimization settings.


Why this matters: Unmanaged updates can restart a workstation during a presentation or critical task. Setting active hours and delivery optimization are standard steps in any enterprise deployment.
