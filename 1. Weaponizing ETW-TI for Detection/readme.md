Microsoft-Windows-WMI-Activity-EventLog & Microsoft-Windows-WMI-Activity-File are Configuration files which are needed to be supplied with Sealighter to Log Events specific to Microsoft-Windows-WMI-Activity Provider. 

One can change the "provider_name" field in the Configuration file to log events from that specific provider.



Microsoft-Windows-WMI-Activity-EventLog Configuration file will output the events directly to EventLog (.EVTX), which can be viewed in EventViewer directly.

Microsoft-Windows-WMI-Activity-File Configuration file will output the events to a File (.json), which can't be viewed in EventViewer.