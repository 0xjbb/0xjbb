## Projects

### EyYoEtwWhereYouAt
Proof of concept tool that monitors kernel events (image loads, process creation, thread creation) and identifies anomalous absences in corresponding ETW telemetry. When system activity occurs without expected ETW events, IE ETW Patching.

### cet-spoofing-detection
This tool is a proof of concept aimed to detect stackspoofing within CET processes. It does this by comparing the shadow stack to the userstack and looks for missing frames. Specifically targeting the modification of unwind data. 

### SuspiciousThreads
A Poc attempt at hunting suspicious thread creation events using ETW only. it currently identifies

- Unbacked Thread creation calls
- Unbacked StartAddress
- JOP based StartAddress
