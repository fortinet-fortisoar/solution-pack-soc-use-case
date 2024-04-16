| [Home](../README.md) |
|----------------------|
# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.   
2. From the list of solution pack that appears, search for and select **SOC Experience**.    
3. Click the **SOC Experience** solution pack card.   
4. Click the **Install** button on the bottom to begin the installation.

## Prerequisites

The **SOC Experience** solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| SP Name                                  | Version         | Purpose                                                                          |
|------------------------------------------|-----------------|----------------------------------------------------------------------------------|
| SOAR Framework                           | 2.1.0 and later | Required for Incident Response modules                                           |
| SOC Simulator                            | 1.0.2 and later | Required for Scenario Module and SOC Simulator connector                         |
| Phishing Email Response                  | 1.0.1 and later | Required to demonstrate investigation of Suspicious Emails                       |
| Brute Force Attack Response              | 1.2.0 and later | Required to demonstrate investigation of Brute Force Attacks                     |
| MITRE ATT&CK Enrichment Framework        | 2.1.0 and later | Required for MITRE Modules and MITRE connector                                   |
| C2 Malware Traffic Response              | 1.0.0 and later | Required to demonstrate investigation of C2 attacks                              |
| Command and Control Response             | 1.0.0 and later | Required to demonstrate investigation of Command and Control attacks             |
| Impossible Traveler Threat Response      | 1.0.0 and later | Required to demonstrate investigation of Concurrent Login type of attacks        |
| Lateral Movement and VPN Breach Response | 1.0.1 and later | Required to demonstrate investigation of Lateral Movement and VPN Breach attacks |
| SOC Overview Metrics                     | 1.0.2 and later | Required for SOC Management Widget and Dashboard                                 |
| Threat Intel Management                  | 1.2.0 and later | Required for Threat Intelligence Modules and Reports                             |
| FortiSIEM Essentials                     | 1.0.0 and later | Required for FortiSIEM integration in FortiSOAR                                  |
| Data Leakage Threat Response             | 1.0.0 and later | Required to demonstrate investigation of Data Leakage Threat attacks             |
| Continuous Delivery                      | 2.0.0 and later | Required to demonstrate CICD                                                     |
| Sankey                                   | 1.0.1 and later | Required for Sankey Widget and Dashboard                                         |

# Configuration

For optimal performance of the **SOC Experience** solution pack, you must configure:

- Threat intelligence connectors to enrich the context of a given indicator
    - To configure and use the VirusTotal connector as a source of threat intelligence, refer to [Configuring Virus Total](https://docs.fortinet.com/document/fortisoar/2.1.0/virustotal/166/virustotal-v2-1-0#Configuration_parameters)

| [Usage](./usage.md) | [Contents](./contents.md) |
|---------------------|---------------------------|