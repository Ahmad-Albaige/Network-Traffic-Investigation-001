

**Network Traffic Investigation – Connection Patterns**



This repo is about a small research done on normal and abnormally functioning network connections from the aspect of a Windows machine.



This project is **not about automating the use of tools** but understanding what normal traffic patterns look like and how repeated or unusual connect attempts are distinguished when contrasted within a normal traffic pattern.



**Scenario**



While analyzing the network data captured on the Windows machine, there were observed to be constant unsuccessful connections on a non-standard port.

These were compared with typical web surfing sessions in order to see whether there were any deviations.



**What was done**



\- Recorded baseline network traffic during typical web browsing activities

\- Recognized typical protocols and ports adopted during normal operation

\- Produced repeated failed connection attempts to a non-standard port

\- Compared the abnormal traffic to the baseline



\- Observations, findings, recommendations, and responses recorded.



**Environment**

\- Windows 10 (vm)



\- Wireshark



\- PowerShell 



Notes

This project is meant for gaining intuition about network behavior and pattern recognition before delving into IDS and SIEM solutions.

Detailed notes and evidence may be found in:

\- `docs/ - "captures/" - `screenshots

