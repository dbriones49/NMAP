# NMAP


## Introduction

NMAP is a powerful network scanning tool used by cybersecurity professionals to identify open ports, services, and potential vulnerabilities on a network. It can be used to conduct comprehensive security audits, monitor network activity, and detect potential threats or unauthorized access. With its extensive range of features and customization options, NMAP is a valuable tool for enhancing the overall security posture of an organization's network infrastructure.

Examples of scans will not be executed or shown here as doing so can be seen as intrusive and potentially unethical, as it involves probing a network without permission.  Therefore I will only explain some command and their purpose.



## Full Open Scan(TCP Connect)
By using the switch -sT, you can gather detailed information about all open ports on a target system, including the services running on those ports. This can help identify potential vulnerabilities and weaknesses that could be exploited by malicious actors

Example: sudo nmap -sT p 80,443 <IP address>

##  Target
This command performs a ping scan to determine which hosts are online on a network. This can help SOC analysts identify active hosts and potential entry points for attackers.

Example: nmap -sP <target>

##  Target
The -sV flag enables version detection, allowing analysts to identify specific services and software versions running on network hosts. This information can be used to assess potential vulnerabilities and prioritize patching efforts.

Example: nmap -sV <target>

##  Target
This command enables aggressive scanning, providing detailed information on operating systems, services, and potential vulnerabilities on network hosts. SOC analysts can use this data to proactively strengthen network defenses.

Example: nmap -A <target>

##  Target
 The -O flag enables OS detection, allowing analysts to identify the operating systems running on network hosts. This information can help analysts tailor security measures to specific OS vulnerabilities and threats.

 Example:nmap -O <target>

# Port
This command scans specific ports on network hosts, helping analysts identify open ports that may be potential entry points for attackers. SOC analysts can then focus on securing these ports to mitigate risks.

Example: nmap -p <port> <target>

# Target
The -sn flag performs a simple host discovery scan without port scanning, providing a quick overview of active hosts on a network. This command can help analysts identify unauthorized devices or potential security breaches within the network.

Example: nmap -sn <target>







## Document Findings and Close out Incident







