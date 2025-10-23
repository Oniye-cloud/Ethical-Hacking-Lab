
| **Aspect**                | **Passive Reconnaissance**                              | **Active Reconnaissance**                   |
| ------------------------- | ------------------------------------------------------- | ------------------------------------------- |
| **Tool Examples**         | `whois`, `theHarvester`, `Google Dorking`, `Shodan`     | `nmap`, `ping`, `netdiscover`, `traceroute` |
| **Data Source**           | Publicly available information (no contact with target) | Directly interacts with the target system   |
| **Risk Level**            | Low                                                     | High                                        |
| **Detection Possibility** | Minimal                                                 | High                                        |
| **Speed**                 | Slower, depends on online data                          | Faster, controlled by tester                |
| **Legal Concerns**        | Usually safe if done ethically                          | Requires permission from the target owner   |




Summary

Passive reconnaissance is best used at the beginning of an assessment to quietly gather public information about a target without alerting them.
Active reconnaissance is used after defining scope and getting permission, to scan and test the target’s live systems for open ports and services. It provides deeper technical details but carries a higher risk of detection.
