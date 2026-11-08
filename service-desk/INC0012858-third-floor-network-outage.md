# INC0012858 — Third Floor Network Outage

**Environment:** Service Desk Simulator (training)  
**Priority:** Critical  
**Status:** Connectivity restored; formal ticket closure not confirmed.

## Incident
All users on the third floor lost internet access for approximately half an hour. Multiple departments were unable to work, and Customer Service could not access its CRM. The second floor remained connected, indicating a floor-specific issue rather than a building-wide outage.

## Investigation
1. Reviewed the incident scope and compared connectivity between floors.
2. Inspected the third-floor network infrastructure through Server Room.
3. Found the **Floor 3 Switch** (10.0.3.1) offline, as reported by the trainee.
4. Rebooted the affected switch using the simulator's infrastructure controls.
5. Asked the reporting employee to retest connectivity.

## Outcome and evidence
The employee confirmed internet access was working again. The simulator displayed **Solution complete**. The post-reboot screenshot shows the Floor 3 Switch **ONLINE** with an uptime of **0 days**, consistent with a recent reboot.

## Technical interpretation
The device is a **network switch**, not a server. Its offline state was the immediate infrastructure failure associated with the third-floor outage. The underlying reason for the switch going offline was not established; rebooting restored service but did not provide root-cause analysis.

## Skills demonstrated
Network infrastructure troubleshooting; incident scope assessment; switch operations; service restoration; high-priority incident handling; user verification of recovery.

## Documentation notes
The trainee has reported using identity verification and the internal Knowledge Base as a general practice, but these steps were not individually reconfirmed for this specific ticket. Formal closure and any follow-up log review remain unconfirmed.
