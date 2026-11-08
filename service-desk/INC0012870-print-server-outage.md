# INC0012870 — Office-wide Printing Outage

**Environment:** Service Desk Simulator (training)  
**Priority:** High  
**Status:** Service restored; ticket closure not yet confirmed.

## Incident
All printers were reported offline across multiple floors. Legal needed contracts for signing and executive presentations could not be printed.

## Actions and investigation
1. Investigated the office-wide failure using the simulator's infrastructure tools.
2. Inspected the Server Room and the print-server role (PRINT01).
3. Identified the print server as down and rebooted it, according to the trainee.
4. The reporting employee confirmed printing worked again.

## Evidence
The simulator displayed 'Solution complete' and invited ticket closure. The user reported that printing was loading again. The post-recovery server view showed PRINT01 online.

## Limitations
The exact root cause of the outage was not established. Ticket closure, server logs, and the exact reboot procedure were not documented. The trainee generally follows identity verification and Knowledge Base procedures, but those steps were not individually confirmed for this ticket.

## Skills
Server infrastructure triage; print service restoration; incident prioritization; end-user communication; documentation.

## Lesson
When multiple printers fail at once, check shared infrastructure rather than assuming every printer has an independent problem. A reboot may restore service without establishing root cause.