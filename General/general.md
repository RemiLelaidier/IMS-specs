Internship Management System (IMS)
===

## Contents

1. [Introduction](#introduction)
2. [Need for Change](#need-for-change)
3. [Business Functional Requirements](#business-functional-requirements)
4. [Technical Changes](#technical-changes)
5. [Deployment Dependencies](#deployment-dependencies)
6. [Upgrade Existing Data Strategy](#upgrade-existing-data-strategy)
7. [Required Tests](#required-tests)
8. [Pending Questions](#pending-questions)
9. [External resources](#external-resources)

---

Introduction
---

The goal of this document is to provide for Unice an internship management system to simplify the actual process.

Need for Change
---

The initial need came from the current method used to handle students internships. The current process may lead to some problems.


Business Functional Requirements
---

**P1** Current management analysis

**P2** Start working on the IMS

Technical Changes
---

### The current process is :

- Validate the internship with a teacher / anyone
- After validation, the student can grab his convention
- The convention is filled by the student and the company (3 times)
- The administration may affect an academic tutor
- Re-enter extracted info to keep traceability on conventions, what is sent, what is there..
- University send filled convention to "Unice"
- Convention come back and is given to the student

### The goal is :

- The student come on the IMS web app, fill his informations
- The university can keep track of everything on some panel, validate details or send errors e-mails
- After convention "ready", printed for signing and sent to Unice
- When conventions come back, University just have to populate changes (Bulk changes function)
- Emails are sent to students when something change and his tutor, to keep everyone updated (to be defined)


Deployment Dependencies
---

We need to deploy and provide some documentation / training to avoid any problem.


Upgrade Existing Data Strategy
---

Nothing to keep, or need to ask for current data


Required Tests
---

Test driven development - Everything should be tested before merge on master
Check with other students
Check with administration if everything is "great"


Pending Questions
---

- What to use ? On a technology side ?
- Need to define general UI - for students and administrators

External resources
---

- Tool used for this task (old but gold) : http://conv.polytech.unice.fr/conv/


Revisions
===
* **09/10/17** : Initial spec after talk with others by Léonard
