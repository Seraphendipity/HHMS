---
theme:           "night"
transition:      "slide"
highlightTheme:  "monokai"
slideNumber:     false
title:           "HHMS-InitialImpressions"
author:          Elijah T. Rose
---

<style>
.container{
    display: flex;
}
.col{
    flex: 1;
}
img {
    width = 50%;
}
h3{
    /*display: top;*/
}
ul, ol, li, p, h3, h4 {
    text-align: left;
}
</style>







## HHMS - Home Health Monitoring System

- Date: 2020.10.01
- Group Engies
  - Ben Whalin (vaeca21)
  - Terry Edwards (tedwards) 
  - Elijah Rose (elirose)
  - Ziyad Allehaibi (zlehaibi)

note: 

---

## Overview
1. Problem Statement
2. Understanding of Project
3. Stakeholders

note: This presentation seeks to demonstrate our (Group Engies) current understanding of the project problem.
Who are my customers?
What do my customers want?







---

## I. Problem Statement

----

### Project Problem
Disadvantaged individuals in such a position that they cannot reliably care for themselves (and thus require the aide of assisted living)

note: REMOVED SLIDE Context refers to the unspoken assumptions, unknown facts, the beginning situation, the definition of completion, the people involved,the customers, and the institutional processes affected. 
f#### Context
f##### Scope
f##### Scale
f##### Specificatons

----

### Example Scenarios
* How will the equipment/sensors work with each other and communicate with the patient's family member
* Has the patient moved in the last hour?
* Has the patient been to the restroom in the last 3(?) hours
* Was there a concerningly loud noise in the home?
* Has the patient accidentally left an exterior door open for an extended period of time?
* Is the temperature of the home appropriate?
* Has the patient taken their medication(s)?
* What is the body temperature of the patient?
* Has the patient's stove been left on for too long?
* How much water has the patient drank for the day?
* Has the patient bathed?
* Is their a need for a live view of the patient when the family member/guardian desires?


note: this leads into stakeholders







---

## II. Understanding of the Project

----

### Project Description
Open Source Home Health Monitoring System with an API to ~~allow~~ encourage extensibility to third-party devices
* Open Source? 
* Difference of general API hub?


note: may erase as it can be part of ### Specifcations
note: Specifications are a short, 10 second sound bytes that describe what the project is about.
note: **Who** need(s) **what** because **why**.
**What** is the problem or need?
**Who** has the problem or need?
**Why** is it important to solve?


----

#### Outcomes/Deliverables
* ECE Graduates: arguably the most important
* HHMS
  * Connector Software
  * API to attach new instrument
  * Demonstrable instruments (likely outsourced)
  * Machine Learning regarding Worrisome Information
  * Documentation for API and Project
* Project Demonstration and Presentations --> UAB Science Fair

note: Describe, visualize the change. How much more efficient? What will the customer have to do? Will training be required? Will nobody notice but profit increase?

note: Our learning of the design process is arguably the most important outcome. 
Is Deliverable different than Outcomes?







---

## III. Investigation

----

### Stakeholders
  
#### External Stakeholders
* Disadvantaged/Dependents
  * Elderly
  * Sickly
  * Physically/Mentally Handicapped
  * "Disadvantaged": broad, near useless term
    * Those restricted in their daily living such that they require a caretaker and constant checking for survival. (?)

----

* Caretakers (of ~~Disadvantaged~~ Partially-Dependent)
  * Family/Friends/Loved Ones
    * Responsibility differences? (IE parent caretaking child vs child caretaking parent)
    * Guardianship vs. Non-Guardianship
  * Specific Examples
    * Myers
    * Terry
* Designers of Health Devices 
  * DIY-ers(?)
  * Conformance to Regulations/Interfacing

note: 
Is there a better term to use here for "disadvantaged"? Indeed, there almost *must* be. Need to brainstorm a term that is general enough to not needlessly exclude certain users, yet refer specifically to those we need...
Regarding Guardianship, how may the product requirements, constraints, and use cases change in relation to a caretaker with guardianship over the disadvantaged (e.g. parent over child) versus cases where the disadvantaged is in control (e.g. a friend checking on their sick, concious friend)? 
Who is the primary stakeholder? The caretaker or disadvantaged?
Wikipedia - "An assisted living resident is defined as a resident who needs assistance with at least one of the activities of daily living."

----

### Stakeholders

#### Internal Stakeholders
* Senior Design - Mirborzorgi: Acting as representative for the school/department
* Project Mentor - Myers
* Ourselves: as one of the notable work products is our own training in the engineering design process, we have significant personal stakes in learning

note: More broadly, ECE department, Engineering Department, UAB, perhaps even further. Mirborzorgi is entrusted as a representative of his superiors to ensure that the deliverable are met, specifically our training.

----

### Use Cases

----

#### Goals

|  ID   |      DESC      |
| ----- | -------------- |
| GO-01 |  |

----

#### Requirements
TBD: speak with Myers

|  ID   |      DESC      |
| ----- | -------------- |
| CR-01 | Integrated with minimal effort. *What is minimal* |
| CR-02 |  |
| CR-03 |  |
| CR-04 |  |

----

#### Constraints

|  ID   |      DESC      |
| ----- | -------------- |
| CO-01 | Budget of $800 |

note: This will later be formed into a constraints document.

---

## Credit
* Engineering Design, 5th Ed. Dieter & Schmidt.
* Wikibooks - Problem Statements - https://en.wikibooks.org/wiki/General_Engineering_Introduction/Problem_Statement#:~:text=Engineers%20solve%20problems.,a%20description%20of%20the%20problem.&text=A%20Problem%20Statement%20is%20a%20contract%20negotiated%20between%20the%20engineering,of%20making%20a%20problem%20statement.
* Engineering guide to writing correct user stories - Nikita Sobolev https://dev.to/wemake-services/engineering-guide-to-writing-correct-user-stories-1i7f
* Define the Problem - https://www.sciencebuddies.org/science-fair-projects/engineering-design-process/engineering-design-problem-statement
* Assisted Living
  * https://en.wikipedia.org/wiki/Assisted_living
  * https://en.wikipedia.org/wiki/Activities_of_daily_living