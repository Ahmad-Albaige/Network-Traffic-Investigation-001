Investigation Notes



This file will document baseline observations, evidence, findings, and recommendations.



Baseline observations (normal traffic)



\- Background traffic is present even when the system is idle.

\- Loading a normal website generates DNS queries followed by HTTPS traffic (TCP port 443).

\- Connections are short-lived and complete successfully.



Unusual findings (connection patterns)



In a short time, it was observed that there were many repeated TCP connection attempts on the external IP address 1.1.1.1 and port 81.

The connections were unsuccessful and did not complete.



The baseline web traffic, which used typical ports such as port 443, is different from this behavior.



Conclusion



Anomaly in the network activity is shown where there are repeated disconnection attempts from a non-standard port. Repeated attempts from a non-standard port might mean automated processes, misconfigurations, and some level of early-stage reconnaissance, but it is not malicious activity.



Recommended actions

Identify which process has the task of attempting to connect.

However, if it connects, it becomes just another device on the Look out for any more unusual network activity from the host. If possible, associate with login or end-point logs.

