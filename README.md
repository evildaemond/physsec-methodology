# Physsec Methodology

Author: 
- [evildaemond](https://github.com/evildaemond)

Contributers: 
- [Topy](https://twitter.com/infosecfriends)

## Quickstart

Want to just get started using this methodology, download the file below from our releases, we have pre-generated a set of generic methodologies as CSV files, easily imported directly into Excel or Word.

| Physical Site Audit | Physical Penetration Test | Generic Red Team Engagement | Everything |
| --- | --- | --- | --- |
|  |  |  |  |

## Who is this for?

This is a methodology primarily designed for Physical Security Auditing, however it is designed in a way that it can be used by penetration testers, red teams, blue teams, security consultants, and other groups.

## Definitions

There are some terms in here which may not mesh with local or industry specific terminology, so we have defined certain terms within this to allow for someone to understand what each term means, with the aim being to avoid miscommunication.

### Where the issue is found

This is a loose categorisation to where an issue is likely to occur, for example an issue of the fire mode on a elevator not triggering an alert would usually fall under a BMS/SMS Configuration and Implementation. These are loose categorisations meant to assist with scoping, sometimes you’re only scoped to complete certain tasks, this allows you to loosely filter out categorises. 

### Backup and Redundancy

Configuring backups and setting up redundancy is a key part of the continuous lifecycle of a system, these systems need to be maintained and kept online during their use. This category encapsulates issues where these redundancies and backups are working as intended or expected. 

### BMS/SMS Configuration and Implementation

Building Management Systems or Security Management Systems can be either configured or implemented in an ineffective way, this category encompasses issues either in the implementation of these systems, or within the configuration, both of which can be modified by the end user, and not a fault of the vendor, but could be a fault of the installer.

### Building or Facility Design and Implementation

Buildings and Facilities are not always designed to be secure, faults within this category are caused by the design of the building or facility, or the implementation of that design, usually the design of the building or facility cannot be directly changed by the end user, but happen at the architectural design or fitting stage, otherwise the implementation not matching the specifications provided during the installation.

### CCTV Monitoring/Recording

Closed Circuit Television Systems operate to record and monitor areas within a location, however the implementation, design and configuration can cause security issues, this category encompasses these issues.

### Documentation

Documentation and document requirements are a important part in maintaining correct and accurate information in the event of a security incident. The category encapsulates the issues around documentation and failures in their maintenance. 

### Doors

Doors act as a physical barrier between an insecure location to a secure location, these doors can be found to have faults and issues which occur at the design and installation stage. The issues here are not fixable by configuration, and usually require physical modification or replacement of components.

### Keys and Key Systems

Keys and Key Systems are faults within the implementation of the key system in use, or a key which is found. These issues are usually only identified at the implementation stage, and depending on the local legal requirements, can be remediated by an end user. 

### Locks

Lock Systems (Not to be confused with Keys and Key Systems) are issues with the locks used as a form of access control, these issues can be identified during the implementation stage, and depending on the local legal requirements, can be remediated by an end user. 

### Security Training and Hygiene

Security Training and Hygiene issues are issues surrounding the people or human processes found within a facility, these issues are considered configuration, which means they can be taught in some way to avoid these issues.

### Surveillance Detection and Response

Issues found within the Surveillance Detection and Response are focused around how a response team or security incident is completed, these issues are considered configuration, which means they can be taught in some way to avoid these issues.

### RFID Access Control Systems

RFID Access Control Systems (Otherwise known as PACS/EACS) are focused around the implementation of physical barriers using RFID Access Control Systems, these issues can be found within the implementation, design, configuration, or a vendor issue. 

### Type of Issue

When we identify issues, we want to highlight what that issue is, where it appears, and what the issue could be categorised as, this allows us to identify trends or how these issues could be grouped when remediating findings.

### Fault in BMS/SMS

Building management systems (BMS) and security management systems (SMS) can hold faults within their entire technical stacks, however this focuses around issues specifically outside of the configuration and instead issues found within the construction, implementation or another error source within the system.

### Improper Installation

During installation and implementation of a environment, faults can occur as a result of mistakes during installation, these faults can usually be remediated during the installation and after the fact by modifications to the existing system

### Logging of Security Events

Security events can come in many shapes and forms, the key part is they are logged somewhere and maintained. If something is not logged, it didn’t happen.

### Logic Faults

Logic faults are less technical faults and more failures in the process or order of operations used within the system. These logic faults can occur on multiple levels, but are usually changed based upon a modification to the process in use or its order of operations. 

### Occupational Health and Safety

While Security may be the aim, health and saftey for others is mostly considered a higher priority,. these issues are ones where the health and saftey of other humans is directly impacted by this issue.

### Out of Specification

Specifications exist for a lot of security systems, these specifications exist as a method of providing a standardised way to measure and implement controls. This category covers instances where a specification or standard was not met.

### Security Enhancement

This category encompases the final class, these are considered security enhancements, they may not be tied directly to a standard or specification, however they allow for a 

### Evidence of Exploitation

Evidence of exploitation is a term used for the indicators of an issue being exploited, this is different from potential damage incurred during testing. In the case of Evidence of Exploitation, the evidence left would allow for someone to identify that an action was taken, which could be used to fingerprint possible attacks after an intrusion.

### Covert

Covert Exploitation means that the exploitation of the issue leaves subtle indicators that would require analysis or detailed forensic inspection to identify if it was exploited, examples include

- Lockpicking attempts of a lock, where the scratches on the brass barrel or pins leave imprints on the inside of a lock
- Damage on the insulation of communication wires for a BMS/SMS as a result of splicing in a tool

### Overt

Overt Exploitation means that the exploitation of the issue leaves clear and visible indicators of exploitation that a casual observer or member of the general public would be able to identify, an example may include;

- A door being rammed or kicked to disconnect it from the frame
- A hole being drilled into a wall

### Surreptitious

Surreptitious Exploitation means that the exploitation of the issue leaves no indicators of exploitation which can be identified or requires highly specialised techniques to identify, examples include;

- Commonly keyed systems, where a lock is keyed alike to another lock which is not managed by your organisation
- Duplication of an RFID Credential

### Potential damage incurred during testing

Potential damage incurred during testing is a specific category which is used as a measure of how much damage is caused if a person was to test the vulnerability. For example, if you are on a site visit for a client, they may look poorly on a fresh door being damaged during a test.

### No identifiable signs of damage

During the course of testing for this issue, there is no identifiable signs of damage, this will mean that a casual observer would not be able to identify the damage as a result of testing, and even detailed review would struggle to identify any damage caused.

Example of this include stealing legitimate keys and using them. 

Forensic review may show changes to the operation or cosmetics, however no changes should be distinct enough to be identified as a result of testing.

### Minor Cosmetic Damage

During the course of testing for this issue, minor damage will be caused to the cosmetic appearance of the item being tested, this damage would be faint and not identifiable by a casual observer, but could be identified if the item was reviewed. Examples include scrapes and scratches from metal tools on the latch of a door.

Forensic review would show the cosmetic damage caused, and the damage caused would be identifiable in a forensic investigation.

### Major Cosmetic Damage

During the course of testing for this issue, major damage will be caused to the cosmetic appearance of the item being tested, this damage would be clearly identifiable by a casual observer. Examples include drilling through a door, or removing a vent.

### Minor Operational Damage

During the course of testing for this issue, minor operational damage will be caused, this would be small changes to the operation of the device in use, these changes could be identified by a casual observer, but would be disregarded, and may be identified by a detailed review. Examples include picking a lock with an automatic pick gun, causing the pins to change or deform enough that a noticable change would have occurred.

### Major Operational Damage

During the course of testing for this issue, major changes to the operation of the device will happen, these changes would be clearly identifiable by a casual observer, they could be disregarded still, and a detailed review would clearly point to the issue being tested.

### Completely Out of Operation

During the course of testing for this issue, the damage caused would cause the item in question to no longer be in operation, this would clearly be identifiable to a casual observer, would not be disregarded, and any review would clearly point to the issue being tested. Examples include cutting a padlock with bolt cutters or cutting through a plasterboard wall.

### Security Level

Security Level is a term used to generalise the type of threat who is using these forms of issues, this is incredibly important for threat emulation against an organisation, not every organisation has the expectation they are being targeted by a Nation State Attacker using undisclosed weaknesses in their systems in use.

### Security Level 1

The Security Level 1 aims to emulate a threat actor who has general tools and equipment, acting in an unskilled way, the threat would not be expected to have training beyond what could be found from common sources such as popular movies, or online videos.

This level of security maturity is expected to hamper the abilities of this threat actor, offering a small level of resistance from any form of attack using this set of tools and knowledge, for a short period of time.

### Security Level 2

The Security Level 2 aims to emulate a threat actor who has non-specialist tools and equipment, acting in an untrained way, the threat would be expected to some basis understanding and knowledge but not have training beyond what could be found from public online sources.

This level of security maturity is expected to hamper the abilities of this threat actor, offering a a medium level of resistance from any form of attack using this set of tools and knowledge, for a limited period of time.

### Security Level 3

The Security Level 3 aims to emulate a threat actor who has specialist tools and equipment, acting in a trained way, the threat would be expected to be highly capable and have some level of professional training.

This level of security maturity is expected to hamper the abilities of this threat actor, offering a a medium level of resistance from any form of attack using this set of tools and knowledge, for a reasonable period of time.

### Security Level 4

The Security Level 4 aims to emulate a threat actor who has specialist tools and equipment, acting in a professional manner, the threat would be expected to be highly capable, equipped with expertise in the field, and would be considered a SME (Subject Matter Expert).

This level of security maturity is expected to hamper the abilities of a threat actor, offering a extended level of resistance against the from any form of attack using this set of tools and knowledge, for an extended period of time.

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to [https://unlicense.org](https://unlicense.org/)
