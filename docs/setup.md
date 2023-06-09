| [Home](../README.md) |
|----------------------|
# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.   
2. From the list of solution pack that appears, search for and select **SOC Experience**.    
3. Click the **SOC Experience** solution pack card.   
4. Click the **Install** button on the bottom to begin the installation.

## Prerequisites

The **SOC Experience** solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| Solution Pack Name | Purpose                                                  |
|:-------------------|:---------------------------------------------------------|
| SOAR Framework     |  Required for Incident Response modules                   |
| SOC Simulator      |  Required for Scenario Module and SOC Simulator connector |
| Phishing Email Response      | Required to demostrate investigation of Suspicious Emails |
| Brute Force Attack Response    |  Required to demostrate investigation of Brute Force Attacks  |
| MITRE ATT&CK Enrichment Framework | Required for MITRE Modules and MITRE connector |
| C2 Malware Traffic Response | Required to demostrate investigation of C2 attacks |
| Command and Control Response | Required to demostrate investigation of Command and Control attacks |
| Lateral Movement and VPN Breach Response | Required to demostrate investigation of Lateral Movement and VPN Breach attacks |
| FortiSIEM Essentials | Required for FortiSIEM integration in FortiSOAR |
| Impossible Traveller Threat Response | Required to demostrate investigation of Concurrent Login type of attacks |
| Data Leakage Threat Response | Required to demostrate investigation of Data Leakage Threat attacks |
| SOC Overview Metrics | Required for SOC Management Widget and Dashboard |
| Threat Intel Management | Required for Threat Intellgence Modules and Reports |
| Continuous Delivery | Required to demostrate CICD |

# Configuration

For optimal performance of the **SOC Experience** solution pack, you must configure:

- Threat intelligence connectors to enrich the context of a given indicator
    - To configure and use the VirusTotal connector as a source of threat intelligence, refer to [Configuring Virus Total](https://docs.fortinet.com/document/fortisoar/2.1.0/virustotal/166/virustotal-v2-1-0#Configuration_parameters)