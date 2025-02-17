# anf-samples
This collection of Amazon Network Firewall templates, demonstrates automated approaches involving an AWS Network Firewall Rule Group, paired with an AWS Lambda function to perform steps like, parsing an external source, and keeping the Rule Group automatically up to date.
  
## File Structure
This project consists of CloudFormation Templates and snippets of source code that demonstrate the functional aspects of the approach.

## Examples

#### Abuse.CH
* Examples of using URLs hosting IP addresses, hostnames, or Suricata rules from https://abuse.ch

#### Emerging Threats
* Example of using URLs hosting IP addresses, hostnames, or Suricata rules from https://rules.emergingthreats.net/fwrules/emerging-Block-IPs.txt

#### SpamHaus
* Examples of using URLs hosting IP addresses, hostnames, or Suricata rules from https://www.spamhaus.org

#### TLS Fingerprint
* An example that uses an Amazon Network Firewall Domain List, partnered with a stateful Suricata rule group to fetch and enforce the TLS Fingerprint of the domain

#### TOR Project
* Examples of using URLs hosting IP addresses, hostnames, or Suricata rules from https://check.torproject.org/exit-addresses

## Architecture Diagram
<img src=/ANFSamplesOverview.png>

## Getting Started

#### 01. Clone the repository
* Clone the repository:

#### 02. Deploy the AWS Network Firewall Rule Group Automations solution:
* Using AWS CloudFormation, create a Stack from the templates available in the deploment folders from where you cloned the deployment assets.

***

## License Summary

This sample code is made available under the MIT-0 license. See the LICENSE file.