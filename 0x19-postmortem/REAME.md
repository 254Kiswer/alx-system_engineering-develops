# Issue Summary
**Duration:** 3 hours (May 10, 2023 1:00 PM - 4:00 PM PDT)
**Impact:** Users experienced intermittent service disruptions and slow page load times, with up to 50% of users affected.
**Root cause:** A misconfiguration in the load balancer resulted in excessive traffic to a single server, causing it to become overloaded and fail to respond.
# Timeline
- **1:00 PM:** Issue first detected by monitoring alerts.- **1:10 PM:** Investigation begins, with focus on load balancer configuration.- **1:30 PM:** Initial assumption is that load balancer configuration is correct, focus shifts to server health.- **2:00 PM:** Misleading investigation into server hardware, leading to no resolution.- **2:30 PM:** Issue escalated to senior sysadmin team for further investigation.- **3:00 PM:** Root cause identified as load balancer misconfiguration, and fix applied.- **4:00 PM:** Incident resolved, all systems operating normally.
# Root cause and resolution
The root cause of the issue was a misconfiguration in the load balancer, resulting in excessive traffic to a single server. This server became overloaded and failed to respond, causing service disruptions and slow page load times for up to 50% of users.
To resolve the issue, the misconfiguration in the load balancer was corrected, ensuring that traffic was distributed evenly among all servers. Additionally, the affected server was restarted and monitored for any further issues.
# Corrective and preventative measures
To prevent similar incidents from occurring in the future, the following tasks will be addressed:
- Review and update load balancer configuration to ensure even traffic distribution.- Implement automated monitoring of server health and traffic distribution.- Conduct regular load testing to identify potential capacity issues before they occur.
