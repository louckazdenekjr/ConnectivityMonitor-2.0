# ConnectivityMonitor-2.0

This is a simple batch script that periodically checks internet connectivity and alerts the user using a stock alarm sound if it goes down. 

Known issues: Since this works based on singular pings it can trigger a false alarm when there is a lot of packet loss on your network. 
Only works when sound is turned on in Windows.

If the script isn't working make sure the device/adapter name is the same as the one you wish to monitor.
