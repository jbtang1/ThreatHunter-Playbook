# Moafee
## Description
[[Group/G0002|Moafee]] is a threat group that appears to operate from the Guandong Province of China. Due to overlapping TTPs, including similar custom tools, Moafee is thought to have a direct or indirect relationship with the threat group [[Group/G0017|DragonOK]]. .Haq 2014
## Attribution
| Tactic | Technique | Tool | Description |
|--------|---------|-------|---------|
| Defense Evasion |                      Binary Padding                   |  |                        [[Moafee]] has been known to employ binary padding.Haq 2014 |                        
| Defense Evasion Privilege Escalation | DLL Injection                    |   PoisonIvy, Poison Ivy | [[PoisonIvy]] can load DLLs.FireEye Poison Ivy |                                     
| Collection Credential Access |         Input Capture                    |   PoisonIvy, Poison Ivy | [[PoisonIvy]] contains a keylogger.FireEye Poison Ivy |                              
| Command and Control |                  Standard Cryptographic Protocol  |   PoisonIvy, Poison Ivy | [[PoisonIvy]] uses the Camellia cipher to encrypt communications.FireEye Poison Ivy |



