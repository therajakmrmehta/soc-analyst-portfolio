# SOC Types and Roles:

## What is a SOC? 
A Security Operations Center (SOC) is a team responsible for monitoring, detecting, analyzing, and responding to cybersecurity threats.

## Types of SOC Models

Depending on your security needs and budget, there are several types of SOCs:

**In-house SOC:**

This team is formed when an organization builds its cybersecurity team. Organizations considering an internal SOC should have a budget to support its continuity.

**Co-Managed SOC:**

The Co-Managed SOC consists of internal SOC staff working with an external Managed Security Service Provider (MSSP). Coordination is key in this type of model.

**Command SOC:**

This SOC team oversees smaller SOCs across a large region. Organizations using this model include large telecommunications providers and defense agencies.

# People, Process, and Technology

- People: The security team responsible for monitoring, detecting, and responding to threats.
- Process: The procedures and steps followed to handle security events and incidents.
- Technology: The tools and systems used to protect an organization's network, devices, and data.

## SOC Roles

**1\. SOC Tier 1 Analyst:**

   Monitors security alerts, performs initial investigations, identifies suspicious activity, and escalates serious alerts.

**2\. SOC Tier 2 Analyst:**

    Investigates escalated alerts, analyzes security incidents, and helps contain threats.

**3\. SOC Tier 3 Analyst:**

    Handles advanced threats, performs threat hunting, and investigates complex security incidents.

**4\. SOC Manager:**

    Manages the SOC team, oversees daily operations, and ensures security procedures are followed.

**5\. Incident Responder:**

    Investigates security incidents, helps contain attacks, and supports recovery.

**6\. Threat Hunter:**

    Proactively searches for hidden threats that may not have been detected by security tools.

**7\. Security Engineer:**

    Designs, implements, and maintains security systems and tools to protect an organization's networks, systems, and data from cyber threats.
**Note:**   SOC roles and responsibilities may vary between organizations.

## SOC Analyst and Their Responsibilities

A SOC Analyst monitors, detects, investigates, and responds to security threats to protect an organization's systems and data.

**Responsibilities:**

**- Monitor Alerts:** 

    Monitor security alerts using SIEM tools.
**- Investigate Threats:* 

    Analyze suspicious activities, logs, and events.
**- Detect Attacks:** 
   
    Identify potential cyberattacks and malicious behavior.
**- Analyze Evidence:** 

    Examine IP addresses, URLs, files, and system logs.
**- Respond to Incidents:** 

    Follow security procedures to handle confirmed threats.
**- Escalate Alerts:** 

    Forward complex or serious incidents to the appropriate security team.
**- Document Findings:** 

    Record investigation steps, evidence, and results.
**- Reduce False Positives:**

    Identify alerts that do not represent real security threats.

## SIEM and Analyst Relationship

**SIEM (Security Information and Event Management):** 

    A tool that collects and analyzes security logs from different sources to detect suspicious activities and generate alerts.

**SOC Analyst:** 

    Uses SIEM to monitor alerts, investigate suspicious activities, identify potential threats, and respond to security incidents.

## Log Management: 

  The process of collecting, storing, organizing, and analyzing logs from systems, applications, and network devices to monitor activities, troubleshoot problems, and detect security threats.

## EDR – Endpoint Detection and Response

  A security technology that continuously monitors endpoint devices, such as computers and servers, to detect suspicious activities, investigate threats, and respond to cyberattacks.

## SOAR (Security Orchestration, Automation, and Response)

   A security technology that connects security tools and automates repetitive tasks to help SOC Analysts investigate alerts and respond to security incidents faster.

   **Some SOAR products commonly used in the industry:**

    -Splunk Phantom
    -IBM Resilient
    -Logsign
    -Demisto

## Playbooks

   Predefined steps or workflows that guide security teams or automate actions to investigate and respond to security incidents.

    Example: Detect a phishing email → Analyze the URL → Block the malicious URL → Notify the SOC Analyst.

## Threat Intelligence Feed

  A continuously updated source of information about known cyber threats, such as malicious IP addresses, domains, URLs, and file hashes, used to help detect and investigate attacks.

    Example: A SOC Analyst checks a suspicious IP address against a threat intelligence feed to see if it is known to be malicious.

## Sandbox

  A secure, isolated environment used to run and analyze suspicious files, programs, or URLs without exposing the main system to potential threats.

    Example: A SOC Analyst runs a suspicious email attachment in a sandbox to check whether it contains malware.
