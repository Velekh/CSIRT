| Telemetry Feature Category | Sub-Category | Sysmon | Carbon Black | Cortex XDR | CrowdStrike | Cybereason | ESET Inspect | Elastic | FortiEDR | Harfanglab | LimaCharlie | MDE | Qualys | SentinelOne | Symantec SES | Trellix | Trend Micro | Uptycs | WatchGuard | Heimdal | Defender P1 | Defender P2 | SEP |
|--------------------------|--------------|---------|---------------|-------------|-------------|------------|--------------|----------|-----------|-------------|-------------|------|---------|-------------|--------------|---------|-------------|---------|------------|----------|--------------|--------------|-----|
| Process Activity | Process Creation | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| | Process Termination | ✅ | ⚠️ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ❌ | ✅ | ✅ | ✅ | ❌ | ✅ | ❌ | 🎚️ | ❌ | ❌ | ⚠️ | ✅ | ✅ | ⚠️ |
| | Process Access | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ | ✅ | ✅ | ⚠️ |
| | Image/Library Loaded | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| | Remote Thread Creation | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | ✅ | ❌ |
| | Process Tampering Activity | ✅ | ⚠️ | ⚠️ | ✅ | ❓ | ❌ | ✅ | ❌ | ✅ | ✅ | ✅ | ❌ | ⚠️ | ✅ | ✅ | ✅ | ✅ | ❌ | ⚠️ | ✅ | ✅ | ❌ |
| File Manipulation | File Creation | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ | ✅ | ✅ | ✅ |
| | File Opened | ❌ | ✅ | ❌ | ⚠️ | ❌ | ❌ | ✅ | 🎚️ | ✅ | ⚠️ | ❌ | ✅ | ❌ | ✅ | ✅ | 🎚️ | ✅ | ⚠️ | ❌ | ❌ | ✅ | ⚠️ |
| | File Deletion | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ✅ | ❌ | ✅ | ✅ | ✅ | ⚠️ |
| | File Modification | ❌ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | 🎚️ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ⚠️ | ✅ | ✅ | ⚠️ |
| | File Renaming | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ✅ | ⚠️ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ | ⚠️ | ✅ | ✅ | ⚠️ |
| User Account Activity | Local Account Creation | ❌ | ❌ | 🪵 | ✅ | ❌ | ✅ | 🪵 | 🪵 | 🪵 | 🪵 | ✅ | 🪵 | ✅ | ❌ | ✅ | 🪵 | 🪵 | ❌ | 🪵 | ✅ | ✅ | ❌ |
| | Local Account Modification | ❌ | ❌ | 🪵 | ⚠️ | ❌ | ✅ | 🪵 | 🪵 | 🪵 | 🪵 | ✅ | 🪵 | 🪵 | ❌ | ✅ | 🪵 | 🪵 | ❌ | 🪵 | ✅ | ✅ | ❌ |
| | Local Account Deletion | ❌ | ❌ | 🪵 | ✅ | ❌ | ✅ | 🪵 | 🪵 | 🪵 | 🪵 | ✅ | 🪵 | 🪵 | ❌ | ✅ | 🎚️ | 🪵 | ❌ | 🪵 | ✅ | ✅ | ❌ |
| | Account Login | ❌ | 🪵 | ✅ | ✅ | ✅ | ✅ | ✅ | 🪵 | ✅ | ⚠️ | ✅ | 🪵 | ✅ | ✅ | ✅ | 🪵 | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ |
| | Account Logoff | ❌ | 🪵 | ✅ | ✅ | ✅ | ✅ | ✅ | 🪵 | ✅ | 🪵 | ❌ | 🪵 | ✅ | ✅ | ✅ | 🪵 | ✅ | ✅ | ✅ | ❌ | ✅ | ⚠️ |
| Network Activity | TCP Connection | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ |
| | UDP Connection | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | 🪵 | ✅ | ✅ | ✅ | ❌ | 🎚️ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ |
| | URL | ❌ | ❌ | ❌ | ✅ | ❌ | ✅ | ⚠️ | ❌ | ✅ | ❌ | ✅ | ✅ | 🎚️ | ⚠️ | ✅ | ❌ | ✅ | ⚠️ | ⚠️ | ✅ | ✅ | ❌ |
| | DNS Query | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| | File Downloaded | ❌ | ❌ | ❌ | ✅ | ⚠️ | ⚠️ | ❌ | ❌ | ❌ | ⚠️ | ✅ | ❌ | ❌ | ❌ | ❌ | ✅ | ⚠️ | ✅ | ⚠️ | ✅ | ✅ | ❌ |
| Hash Algorithms | MD5 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| | SHA | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ |
| | IMPHASH | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ⚠️ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Registry Activity | Key/Value Creation | ✅ | ✅ | ✅ | ⚠️ | ⚠️ | ✅ | ✅ | 🎚️ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ |
| | Key/Value Modification | ✅ | ✅ | ✅ | ⚠️ | ⚠️ | ✅ | ✅ | 🎚️ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ |
| | Key/Value Deletion | ✅ | ✅ | ✅ | ❌ | ⚠️ | ✅ | ✅ | 🎚️ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ |
| Schedule Task Activity | Scheduled Task Creation | ❌ | ❌ | 🪵 | ✅ | ✅ | ✅ | 🪵 | 🪵 | 🪵 | 🪵 | ✅ | 🪵 | ✅ | ❌ | ❌ | 🪵 | 🪵 | ❌ | 🪵 | ✅ | ✅ | ❌ |
| | Scheduled Task Modification | ❌ | ❌ | 🪵 | ✅ | ✅ | ❌ | 🪵 | 🪵 | 🪵 | 🪵 | ✅ | 🪵 | ✅ | ❌ | ✅ | 🪵 | 🪵 | ❌ | 🪵 | ✅ | ✅ | ❌ |
| | Scheduled Task Deletion | ❌ | ❌ | 🪵 | ✅ | ❌ | ❌ | 🪵 | 🪵 | 🪵 | 🪵 | ✅ | 🪵 | ✅ | ❌ | ❌ | 🪵 | 🪵 | ❌ | 🪵 | ✅ | ✅ | ❌ |
| Service Activity | Service Creation | ❌ | ⚠️ | 🪵 | ✅ | ✅ | ✅ | 🪵 | 🪵 | 🪵 | ✅ | 🪵 | ✅ | ✅ | ❌ | ❌ | 🪵 | ✅ | ⚠️ | ⚠️ | 🪵 | ✅ | ❌ |
| | Service Modification | ❌ | ❌ | 🪵 | ⚠️ | ❌ | ❌ | 🪵 | 🪵 | 🪵 | ✅ | ❌ | ✅ | 🎚️ | ❌ | ✅ | 🪵 | ✅ | ⚠️ | ⚠️ | ❌ | ✅ | ❌ |
| | Service Deletion | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | 🪵 | 🪵 | ❌ | ❓ | ❌ | ❌ | ❌ | ❌ | ❌ | 🪵 | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| Driver/Module Activity | Driver Loaded | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | 🎚️ | 🪵 | ❌ | ✅ | ✅ | ✅ | ❌ |
| | Driver Modification | ❌ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| | Driver Unloaded | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ⚠️ | ❌ | ❌ | ❌ | 🪵 | ❌ | ❌ | ❌ | ✅ | ❌ |
| Device Operations | Virtual Disk Mount | ❌ | ❌ | ⚠️ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ✅ | ❌ |
| | USB Device Unmount | ❌ | ❌ | ⚠️ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ⚠️ | ✅ | ❌ | 🎚️ | 🎚️ | ❌ | ❌ | ✅ | ✅ | ⚠️ | ✅ | ✅ | 🎚️ |
| | USB Device Mount | ❌ | ⚠️ | ⚠️ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ⚠️ | ✅ | ❌ | 🎚️ | 🎚️ | ❌ | ❌ | ✅ | ✅ | ⚠️ | ✅ | ✅ | 🎚️ |
| Other Relevant Events | Group Policy Modification | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ | ❌ | ❌ | 🪵 | ❌ | ❌ | ✅ | ✅ | ❌ |
| Named Pipe Activity | Pipe Creation | ✅ | ⚠️ | ❌ | ✅ | ❌ | ✅ | ❌ | ❌ | ✅ | ✅ | ✅ | ❌ | 🎚️ | ❌ | ❌ | 🎚️ | ✅ | ❌ | ⚠️ | ✅ | ✅ | ❌ |
| | Pipe Connection | ✅ | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ | ❌ | 🎚️ | ❌ | ✅ | 🎚️ | ❌ | ❌ | ❌ | ✅ | ✅ | ❌ |
| EDR SysOps | Agent Start | ✅ | ✅ | ⚠️ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | 🪵 | ✅ | ✅ | 🎚️ | ❓ | ❌ | ✅ | ❌ | ✅ | 🪵 | ✅ | 🎚️ |
| | Agent Stop | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ❌ | ✅ | ✅ | 🪵 | ✅ | ✅ | 🎚️ | ❓ | ❌ | ✅ | ❌ | ✅ | 🪵 | ✅ | 🎚️ |
| | Agent Install | ❌ | ✅ | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | 🪵 | ✅ | ✅ | 🎚️ | ✅ | ❌ | ❌ | ✅ | ✅ | 🪵 | ✅ | 🎚️ |
| | Agent Uninstall | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ✅ | 🎚️ | ✅ | ❌ | ❌ | ✅ | ✅ | ❌ | ✅ | 🎚️ |
| | Agent Keep-Alive | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | 🪵 | ✅ | ✅ | 🎚️ | ❓ | ❌ | ❌ | ❌ | ✅ | 🪵 | ✅ | 🎚️ |
| | Agent Errors | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | 🎚️ | ❓ | ❌ | ✅ | ❌ | ✅ | ✅ | ✅ | 🎚️ |
| WMI Activity | WmiEventConsumerToFilter | ✅ | ❌ | 🎚️ | ✅ | ✅ | ✅ | ✅ | 🪵 | ✅ | ❌ | ✅ | 🪵 | ✅ | ⚠️ | ✅ | 🪵 | ✅ | ✅ | ⚠️ | ✅ | ✅ | ⚠️ |
| | WmiEventConsumer | ✅ | ❌ | 🎚️ | ✅ | ✅ | ✅ | ✅ | 🪵 | ✅ | ❌ | ✅ | 🪵 | ✅ | ⚠️ | ✅ | 🪵 | ✅ | ✅ | ⚠️ | ✅ | ✅ | ⚠️ |
| | WmiEventFilter | ✅ | ❌ | 🎚️ | ✅ | ✅ | ✅ | ✅ | 🪵 | ✅ | ❌ | ✅ | 🪵 | ✅ | ⚠️ | ✅ | 🪵 | ✅ | ✅ | ⚠️ | ✅ | ✅ | ⚠️ |
| BIT JOBS Activity | BIT JOBS Activity | ❌ | ❌ | 🎚️ | ✅ | ❌ | ❌ | ❌ | 🪵 | ❌ | ❌ | ❌ | ✅ | ❌ | ❌ | ✅ | 🪵 | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| PowerShell Activity | Script-Block Activity | ❌ | ✅ | 🪵 | ✅ | ❌ | ✅ | 🪵 | 🪵 | ✅ | 🪵 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ | ⚠️ |

Legend:
- ✅ Full Support
- ⚠️ Partial/Limited Support
- ❌ No Support
- 🎚️ Configurable/Optional
- 🪵 Event Log Only
- ❓ Unknown/Unclear Support
