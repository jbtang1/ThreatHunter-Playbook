# Darkhotel
## Description
[[Group/G0012|Darkhotel]] is a threat group that has been active since at least 2004. The group has conducted activity on hotel and business center Wi‑Fi and physical connections as well as peer-to-peer and file sharing networks. The actors have also conducted spearphishing.Kaspersky Darkhotel
## Attribution
| Tactic | Technique | Tool | Description |
|--------|---------|-------|---------|
| Defense Evasion |              Code Signing                         |  | [[Darkhotel]] has used code-signing certificates on its malware that are either forged due to weak keys or stolen.Kaspersky Darkhotel |          
| Collection Credential Access | Input Capture                        |  | [[Darkhotel]] uses a sophisticated keylogger.Kaspersky Darkhotel |                                                                               
| Lateral Movement |             Replication Through Removable Media  |  | [[Darkhotel]]'s selective infector modifies executables stored on removable media as a method of spreading across computers.Kaspersky Darkhotel |
| Persistence |                  Registry Run Keys / Start Folder     |  | [[Darkhotel]] has been known to establish persistence by adding programs to the Run Registry key.Kaspersky Darkhotel |                           
| Lateral Movement |             Taint Shared Content                 |  | [[Darkhotel]] uses a virus that propagates by infecting executables stored on shared drives.Kaspersky Darkhotel |                                



