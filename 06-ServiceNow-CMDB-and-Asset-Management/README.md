# ServiceNow CMDB & Asset Management

## Overview

This lab focuses on how ServiceNow can be used to keep track of IT assets and configuration items through the CMDB.

The goal was to understand the difference between an IT asset and a configuration item, how CI records are organized in ServiceNow, and why accurate CMDB information matters during day-to-day IT support.

---

## What I Worked On

- Explored the ServiceNow CMDB
- Reviewed configuration item records
- Worked with common CI information such as name, class, status and ownership
- Reviewed IT asset information
- Compared asset records with configuration items
- Looked at how CMDB information can support incident investigation and IT operations

---

## CMDB

The Configuration Management Database provides a central place for storing information about the systems and services managed by IT.

A CI can represent things such as:

- computers
- servers
- network devices
- applications
- services

Each CI contains information that helps support teams understand what the item is and how it is being managed.

---

## Asset vs Configuration Item

One of the main things I wanted to understand in this lab was the difference between an asset and a CI.

An **asset** is mainly tracked from a business and lifecycle perspective.

Examples include:

- ownership
- purchase information
- assignment
- asset status
- lifecycle

A **configuration item** is tracked because it is part of the IT environment and may affect the delivery or support of a service.

In practice, the same device can be important from both perspectives.

```text
IT Asset
   │
   ├── Ownership
   ├── Assignment
   ├── Lifecycle
   └── Financial information

Configuration Item
   │
   ├── Technical information
   ├── Operational status
   ├── Configuration
   └── Service relationships
```

---

## Reviewing Configuration Items

I used the CMDB interface to review how configuration items are recorded and categorized.

Important information available through CI records includes:

- CI name
- CI class
- operational status
- assigned user or owner
- location
- technical information

Having this information available gives an analyst more context when investigating an issue.

For example, instead of treating an incident as only a ticket, the analyst can identify the device or service involved and review its configuration information.

---

## Asset Management

I also reviewed how ServiceNow tracks IT assets.

Asset management focuses more on the lifecycle of the physical or software asset.

A simplified lifecycle looks like:

```text
Procure
   ↓
Receive
   ↓
Deploy
   ↓
Assign
   ↓
Maintain
   ↓
Retire
```

Keeping these records accurate helps IT teams understand what equipment exists, where it is located and who is responsible for it.

---

## CMDB in Incident Management

The CMDB becomes more useful when it is connected with other ITSM processes.

For an incident, the affected configuration item can provide additional context:

```text
User reports issue
        ↓
Incident created
        ↓
Affected CI identified
        ↓
CI information reviewed
        ↓
Troubleshooting
        ↓
Resolution
```

This can help an analyst understand whether the problem affects a specific device, application or service.

It also creates a better history because incidents can be associated with the systems they affected.

---

## Why CMDB Accuracy Matters

A CMDB is only useful when the information inside it is reliable.

Incorrect or outdated CI information can make troubleshooting harder and reduce confidence in the system.

Some of the important areas to keep accurate are:

- ownership
- assignment
- operational status
- CI classification
- asset status
- relationships

This was one of the main takeaways from the lab. CMDB work is not simply about creating records; the information has to remain useful for the people supporting the environment.

---

## Skills Practiced

- ServiceNow
- Configuration Management Database (CMDB)
- Configuration Items
- IT Asset Management
- Asset lifecycle concepts
- CI classification
- ITSM
- Incident and CI context
- IT service operations

---

## What I Learned

Before working with the CMDB, I mainly thought of asset management as keeping an inventory of computers and other equipment.

This lab helped me understand that CMDB work goes further than inventory. A support analyst needs technical and operational context about the systems involved in an incident.

It also showed me why maintaining accurate asset and CI information is important. A large CMDB with outdated records would not provide much value during troubleshooting.

The main lesson for me was that good configuration data gives IT teams better context when supporting users and services.
