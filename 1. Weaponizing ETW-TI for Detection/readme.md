- **Microsoft-Windows-WMI-Activity-EventLog.json** & **Microsoft-Windows-WMI-Activity-File.json** are Configuration files which are needed to be supplied with Sealighter to Log Events specific to `Microsoft-Windows-WMI-Activity` Provider. 

- One can change the `"provider_name"` field in the Configuration file to log events from that specific provider.

- **Microsoft-Windows-WMI-Activity-EventLog.json** configuration file will output the events directly to EventLog (.evtx), which can be viewed in EventViewer directly.

- **Microsoft-Windows-WMI-Activity-File.json** configuration file will output the events to a File (.json), which can't be viewed in EventViewer.
