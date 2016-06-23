# Freedonia Hello World (freedonia.fd)
This System Security Plan provides an overview of the security requirements for
the Freedonia Hello World (freedonia.fd) system
and describes the controls in place or planned for implementation to provide a level of security appropriate for the information to be transmitted, processed or stored by the system.  Information security is vital to our critical infrastructure and its effective performance and protection is a key component of our national security program.  Proper management of information technology systems is essential to ensure the confidentiality, integrity and availability of the data transmitted, processed or stored by the
Freedonia.fd information system.  

The security safeguards implemented for the
Freedonai.fd system
meet the policy and control requirements set forth in this System Security Plan.  All systems are subject to monitoring consistent with applicable laws, regulations, agency policies, procedures and practices.  

Unique Identifier | Information System Name | Information System Abbreviation
----------------- | ----------------------- | ---
Freedonia.fd | Freedonia Hello World | Freedonia.fd


# Security Objectives Categorization (FIPS 199)
Security Objective | Low, Moderate or High
--------------- |----------
Confidentiality | Low
Integrity       | Low
Availability    | Low

# Information System Categorization
The overall information system sensitivity categorization is noted in the table that follows.

Low | Moderate | High
--- | --- | ---
X    |    |


Using this categorization, in conjunction with the risk assessment and any unique security requirements, we have established the security controls for this system, as detailed in this SSP.

# Remaining information copied from https://github.com/18f/cg-compliance...

## Information Types

The following tables identify the information types that are input, stored, processed, and/or output from Cloud.Gov. The selection of information types is based on guidance provided by OMB Federal Enterprise Architecture Program Management Office Business Reference Model 2.0, and FIPS Pub 199, Standards for Security Categorization of Federal Information and Information Systems which is based on NIST SP 800-60, Guide for Mapping Types of Information and Information Systems to Security Categories.

|Information Type | Confidentiality   | Integrity | Availability|
|-----------------|-------------------|-----------|-------------|
|C.3.5.1 System Development           |Low        | Moderate    | Low
|C.3.5.2 life-cycle/Change Management |Low        | Moderate    | Low
|C.3.5.3 System Maintenance           |Low        | Moderate    | Low      
|C.3.5.4 Infrastructure Maintenance   |Low        | Low         | Low

## E-Authentication Determination

### E-Authentication Question
Yes | No  | E-Authentication Question
--- | --- | ---
 x  |     | Does the system require authentication via the Internet?
 x  |     | Is data being transmitted over the Internet via browsers?
 x  |     | Do users connect to the system from over the Internet?

Note: Refer to OMB Memo M-04-04 E-Authentication Guidance for Federal Agencies for more information on e-Authentication.

The summary E-Authentication Level is recorded in the table that follows.

### E-Authentication Determination
|System Name| System Owner| Assurance Level| Date Approved|
|-----------|
|Cloud.Gov Platform as a Service| 18F/GSA| Level 2| Feb 18, 2016|

## Information System Owner
Name | Title | Organization | Address | Phone Number | Email Address
--- | --- | --- | --- | --- | ---
Noah Kunin | 18F Infrastructure Director | 18F/GSA | 1800 F Street, NW Washington DC 20405 | 202-577-7167 | noah.kunin [at] gsa.gov

## Authorizing Official
Name | Title | Organization | Address | Phone Number | Email Address
--- | --- | --- | --- | --- | ---
Aaron Snow | Authorizing Official | 18F/GSA | 1800 F Street, NW Washington DC 20405 |  | aaron.snow [at] gsa.gov

## Other Designated Contacts
Name | Title | Organization | Address | Phone Number | Email Address
---  | ---   | ---          | ---     | ---          | ---
Diego Lapiduz  | Innovation Specialist |18F/GSA| 1800 F Street, NW Washington DC 20405| 415-730-5945| diego.lapiduz [at] gsa.gov  
Bret Mogilefsky| Program Manager |18F/GSA| 1800 F Street, NW Washington DC 20405| 510-610-1956|bret.mogilefsky [at] gsa.gov

## Assignment of Security Responsibility
Name | Title | Organization | Address | Phone Number | Email Address
----|----|----|----|----|----
Curtis Lovett| Information System Security Officer| 18F/GSA |1800 F Street DC 20405 | 202-412-0337 | curtis.lovett [at] gsa.gov
Rajat Varuni | Information System Security Officer| 18F/GSA |1800 F Street DC 20405 | 202-746-3201 | rajat.ravindervaruni [at] gsa.gov  
Noah Kunin| 18F Infrastructure Director|18F/GSA| 1800 F Street DC 20405| 202-577-7167| noah.kunin [at] gsa.gov

## Information System Operational Status
The system is currently in the life-cycle phase noted in the table that follows.  (Only operational systems can be granted an ATO).

## System Status
Operational | Under Development | Major Modification | Other
--- | --- | --- | ---
X |  |  |

## Information System Type

The Cloud.Gov makes use of unique managed service provider architecture layer(s).

## Cloud Service Models
Information systems, particularly those based on cloud architecture models, are made up of different service layers.  The layers of the Cloud .Gov defined in this SSP are indicated in the table that follows.

X |Platform as a Service (PaaS) | Application
-|-|-
  |Software as a Service (SaaS) | Application
  |Infrastructure as a service (IaaS)| General Support System
  |Other| Explain:


## Cloud Deployment Models

Information systems, particularly those based on cloud services and infrastructures, are made up of different deployment models.  The deployment models of the Cloud.Gov that are defined in this SSP, and are not leveraged by any other Provisional Authorizations, are indicated in the table that follows.

X |**Public** | Cloud services and infrastructure supporting multiple organizations and agency clients|
-|-|-
|Private| Cloud services and infrastructure dedicated to a specific organization/agency and not other clients
|Community| Cloud services and infrastructure shared by several organizations/agencies with the same policy and compliance considerations
|Hybrid| Explain: (e.g., cloud services and infrastructure that provides private cloud for secured applications and data where required and public cloud for other applications and data)

## Leveraged Authorizations

The Cloud.Gov information system plans to leverage a pre-existing Provisional Authorization.  Provisional Authorizations leveraged by this IAWS FedRAMP ATO (issued by the HHS are noted in the table that follows.  

Information System Name | Service Provider Owner | Date Granted
--- | --- | ---
AWS FedRamp Agency ATO (issued by the HHS) | Amazon |	May 13, 2013
