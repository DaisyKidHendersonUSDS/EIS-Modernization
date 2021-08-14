# Usability Research

Version 1.2

December 13, 2018

## Table of Contents
- [Usability Research](#usability-research)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Overview Metrics](#overview-metrics)
  - [Discovery or User Research during each Sprint](#discovery-or-user-research-during-each-sprint)
    - [User Recruitment](#user-recruitment)
      - [SME Assignment](#sme-assignment)
    - [Discovery Session Format](#discovery-session-format)
    - [Discovery Cadence](#discovery-cadence)
  - [Pre-Production Usability Testing](#pre-production-usability-testing)
    - [Test or Story Structure](#test-or-story-structure)
    - [Documentation in Azure DevOps](#documentation-in-azure-devops)
    - [Testing Teams](#testing-teams)
  - [Post Production Usability Testing](#post-production-usability-testing)
  - [Expectations](#expectations)
  - [Challenges](#challenges)

## Introduction
The purpose of the document is to provide an overview of the types of usability testing to be performed over the life of the EIS-Modernization project, and processes specific to usability testing efforts. This document is not applicable to other necessary testing such as developmental, accessibility, and security testing, which is covered in the ARIES project Change Management document. There are four areas from which we will conduct user research to drive successful development:

1. Overview Metrics
2. Discovery user research
3. Pre-Production usability testing
4. Post Production usability testing

We will use the same three metrics for overall usability with which we can gauge our overall success at each increment toward completion milestones in our [roadmap](https://app.mural.co/t/gsa6/m/gsa6/1493828126408/2c1fd30717381a20f4bf251e57a1c344f9e2c3ba), providing an overview. Discovery refers to development testing to drive design. Pre-Production usability testing represents final user testing prior to implementation to meet state technological procedure. Post production usability data collection to assure that we’ve met incremental goals, and to gather information toward design of the next increment.

## Overview Metrics
When developing our product [roadmap](https://app.mural.co/t/dhssalaska0106/m/dhssalaska0106/1576183680860/c1682951c77a41f29cb684cff893ff837f70b084), the ability to gather information at each increment to help us quantify our progress was needed. Metrics provide clarity, and tangible standards by which we can focus our efforts.  We will update the metrics following the completion of each increment toward a milestone in our [roadmap](https://app.mural.co/t/dhssalaska0106/m/dhssalaska0106/1576183680860/c1682951c77a41f29cb684cff893ff837f70b084). 
Our ultimate goal is increased productivity as we move DPA workers into a modern eligibility system. For this reason, the following three measures were chosen: 

1. Applications worked Timely

    Timeliness performance is an important aspect of benefit issuance.   [SNAP applications must be processed and benefits provided within 30 days of the application date, or within 7 days for expedited applications](http://dpaweb.hss.state.ak.us/manuals/fs/fsp.htm). [Medicaid applications must be processed in 45 days](http://dpaweb.hss.state.ak.us/manuals/MAGI2/magi.htm).  The DPA’s Research & Analysis unit, responsible for mandatory federal reporting, regularly produces Timeliness Performance reports.  The report titled “Applications Timeliness” will be used to produce this metric. It measures the percentage of applications processed in a timely manner.  We will average the timeliness performance weighted by percentage of programs offered. As we begin, [our baseline timeliness percentage, across all programs, is 73%, while our goal is 95% timeliness](http://dpaweb.hss.state.ak.us/node/354).

2. Acceptable Error Rate

   Reducing error rates is another important goal. The case management system in use by the DPA (PathOS) contains a reporting feature which allows us to generate a “Twelve Month Summary” report of each program’s error rates. We will average the case error rate weighted by the percentage of total sample cases for all programs. Our baseline error rate across programs is 14%, and our goal is 8%.

3. Applications Per Day Per Eligibility Technician

   Increasing the speed at which we are able to process applications and recertification will provide better service to our clients. By reducing the time a client needs to wait for an eligibility decision, we will reduce the number calls, in person requests to district offices, and duplicate online applications. 

   We work with our PathOS consultant, receiving this information quarterly. 

   The metric will consider the number of applications received in the last quarter, the processing time for each type of application, and the average transaction type to arrive at average applications per day.

   The average transaction time in minutes for each program will be weighted by the volume of applications for that program in relation to all applications. We will use 390 minutes, the expected work time for each day, divide by it the average processing time, which will provide the average applications worked per day per worker.

   Our baseline metric is 6, and our goal is 9 applications per day, per worker. 
   
   These three ‘overall’ metrics will be measured separately through program information analyst’s regularly scheduled divisional reports, and through coordination with case management consultants working with the division as noted above, and shared with stakeholders through the updated metrics on the [roadmap](https://app.mural.co/t/dhssalaska0106/m/dhssalaska0106/1576183680860/c1682951c77a41f29cb684cff893ff837f70b084).

## Discovery or User Research during each Sprint
For each feature implemented, agile methodology implements user testing as a critical first step of each development phase. Each sprint, or period of design and development work, is dependent on user input to drive the design of the feature. 
This user research is to discover whether the work completed in the previous sprint meets the user needs. We discover what works, what needs to be changed, and what may be added to make it better, according to the users who will use the feature.

 ![UsabilityResearchDiagram](../UsabilityResearch/Images/UsabilityResearchDiagram.png)

### User Recruitment
The Division of Public Assistance (DPA) workers are assigned work according to a tight schedule coordinated by their supervisors. Recruitment through volunteer workers is not possible due to this structure.  Coordination with DPA leadership, regional managers and supervisors is needed to obtain permission to “borrow” the workers, and establish the user group. 

The user group, or Subject Matter Experts (SME), will be in place before the vendor begins working. As soon as practicable after the contract has been awarded, a SME group will be assembled with the help of DPA leadership. 

#### SME Assignment

1. DPA director sends SME request to Regional Managers and Supervisors:
   
    a. Description of the contract
    b. How many users are needed
    c. What job roles are needed for the contract
    d. What level of expertise is optimal for the SME group
    e. Time commitment needed
    f. Response deadline
2. Regional Managers and Supervisors respond with list of employee names
3. DPA director forwards SME names to Project Management Office (PMO)
4. PMO sends welcome letter:
    a. Introduces contract purpose
    b. SME participation parameters
        i. Method of research data collection
        ii. Contact and Meeting expectations
    c. Next Steps

Each communication with the user group:
- Is approved by DPA leadership
- Includes DPA leadership
- Provides at least one week’s notice for any needed user participation

### Discovery Session Format
The format of the Discovery session should be as minimally invasive as possible, due to the heavy workloads of all DPA field services staff.

Each session’s purpose is to gather usability information on the present design from users based on prepared scripts; questions about current design elements.

The script’s questions will gather responses as the users navigate through a task in the existing interface or a prototype of the design.  

These sessions delivery format may be conducted using the following methods:
- Recorded guided sessions, where a project team member guides the user(s) through the prototype 
- In person guided sessions, where a project team member guides the user(s) through the prototype
- In person “shadowing”, where a project team member provides minimal instruction and observes and records the user’s navigation
- Self-recorded tours of the feature, where a project team member provides material and instruction
- Surveys
- Diary studies-self-reported data from users over a period of time such as a few days. This method for Discovery necessitates a short diary period, in order to be contained within a two week sprint. 

User responses for all methods used in Discovery will be documented in a Usability Review document. A summary, or synthesis of all user sessions for that sprint, will be constructed based on analysis of that sprint’s discovery session’s documentation. The synthesis findings will be used to direct the development needed for the next sprint.

User participants in all documentation will be anonymized to allow users [freedom of expression](https://github.com/AlaskaDHSS/EIS-Modernization/blob/master/how-we-work.md#accepting-vendor-work). 

The **Usability Review** document will contain:
- Date, Session participants (“SME1” for user participants, names for conductors)
- Link, or example of prototype used
- Topic Headers
- Verbatim text of user responses
  
  Project team member preparation for the usability sessions:
  - Identification of topics
  - Script, or questions crafted aimed at feature evaluation
  - Prototype creation
  - Research observation
  - Note taking assistance
  - Synthesis creation

The **Discovery Synthesis** document will contain:
- Dates of sessions
- Prototype description
- Focus summary: topic or feature user data focus
- Insights: A list of findings-needed element or feature 
  - Effort: the effort needed to support the named insight
- Actions: Needed implemented coordination activity
- Stories to Create: Features defined based on expressed need to be logged as Stories into Azure DevOps. 
- Stories to Change: Feature changes to existing user stories
- Prospective Topics/specific questions for the next sprint

Action toward preparation and execution of usability review and synthesis are documented in Azure DevOps, in the form of Stories and Tasks.

Each feature, or ability, in the newly developed application is in the form of a User Story. Each story has at least one **scenario that serves as the acceptance criteria for the story**. The scenarios describe the expected system behavior for the given user actions, and account for all expected results.

Within each story, there are steps to achieve the scenario’s goal. These steps are used to both develop the code, and to test the functionality.

### Discovery Cadence

The cadence of usability testing during each two week sprint toward completing the increment of development is as follows. The Product team consists of all state project management and technicians, and all contractors assisting. The Project Management office (PMO) consists of the team designated and working solely on the EIS-Replacement project.

| **Week** | **Day** | **Description** | **Responsible** |
| :---: | :---: | :--- | :---: |
| 1 | 1 | Determine what should be tested from previous Sprint and what should be explored in current Sprint | Product Team |
| 1 | 2-4 | Prepare testing materials (script, prototype) | Contractor |
| 2 | 1-3 | Usability testing | PMO |
| 2 | 4 | Tests documented, Synthesis Complete, Stories written | PMO |
| 2 | 5 | Prioritization of Stories/Changes | Product Team |
| 2 | 5 | Design materials prepared for next Sprint | Contractor |

Users should be scheduled immediately following identification of needed user information, early in the first week of the sprint to afford a week’s notice to users and supervisors.   

## Pre-Production Usability Testing
During the last few weeks of a feature contract, we will conduct the State of Alaska technical standards required pre-production usability testing. We will use the opportunity to assure that the feature has met established criteria as defined in the requirements for that feature.  [Technical and information security requirements for pre-production testing are not covered in this document](https://go.dhss.ak.local/intranet/Home/FMSPub/Shared%20Documents/741SystemPlanningandAcceptance.pdf#PageMode=none&navpanes=0&page=1&statusbar=0&toolbar=1&view=FitH).

Our user testing criteria for this type of testing will be based on our Alaska Product Roadmap customer promises, listed with each increment of each milestone.  Each feature developed to support the customer promise will be tested, documented, and linked in Azure DevOps.

The tests will be performed using the below two methods. These methods will be occur in parallel during the Pre-Production testing time period:

1. With designated Subject Matter Experts (SME’s), guided and documented by the EIS-R Project Management Office (PMO). 
    a. Up to 10 Users may receive test cases via email to complete individually and return, with screen shots of the results, to the PMO for logging into Azure DevOps. 
    OR
    b. A group testing session with up to 10 users wherein multiple tests are performed simultaneously within one session. These tests could be performed on location in Staff Development and Training (SD&T) training rooms, with results logged by the PMO into Azure DevOps
2. Independently by Systems operations, accessing test cases from Azure DevOps, and logging results into Azure DevOps.
   
Test cases will be written from the steps iterated for each scenario of each story in Azure DevOps.

### Test or Story Structure
Each feature, or ability, in the newly developed application is in the form of a User Story. Each story has at least one **scenario that serves as the acceptance criteria for the story**. The scenarios describe the expected system behavior for the given user actions, and account for all expected results. 

Within each story, there are steps to achieve the scenario’s goal. These steps are used to both develop the code, and to test the functionality. For all of the stories developed for the feature, test stories are written using the scenarios.

See details in [User Story Standards](https://alaskadhss.visualstudio.com/Dpa/_wiki/wikis/Dpa.wiki?wikiVersion=GBwikiMaster&pagePath=%2FWelcome%20to%20the%20EIS%20M%20Project%2FUser%20Story%20Standards&pageId=61).

### Documentation in Azure DevOps
Each user story describing a feature will be linked to tests for each scenario within that story. 

As each scenario is tested, the results are attached to the test item, and marked “Ready” if successful. When all scenarios are tested successfully, the Story is complete and ready for production.
If any test, or scenario within a story, fails, a ‘bug’ is opened in Azure DevOps, and attached to the test.  Bugs are linked to tests, and all tests are linked to the Story. No story is complete and ready for production until all user tests (all scenarios) are successful. 

Each test’s screenshot(s) should demonstrate that the scenario described has been proved, or has failed.
In the case of failure, a Bug is created and linked to the test case. 

Each Bug’s title should clearly state the failure, as should each screenshot attached.

Comments should be as complete as possible when reporting bugs:
- What were you trying to do?
- Include any relevant screenshots or pictures

- What happened?
- What should have happened?
- With as much detail as possible, what are the steps to reproduce the issue?
It will be the responsibility of both PMO and Systems operations to complete the tests and log bugs as needed into Azure DevOps.

### Testing Teams
The User testing team will be comprised of SME’s who have been involved in the development of the application, as well as systems operations testers.
- The PMO will notify systems operation at least two weeks in advance of final user testing before the feature is released into production.

## Post Production Usability Testing
When each increment in our milestone is completed we will assure that the feature has met established criteria based on user need.  After implementation of an incremental feature, we’ll again gather information to determine our progress in meeting our customer promises. 

We’ll also need to begin collecting information from all users on the implemented feature toward correction of any bugs that are discovered.

To launch this effort after release, we’ll release a short user survey via email to all DPA field workers. We will use the results of this survey to assist us in determining whether we have met our promises for that feature toward refining our development planning.

Coordinating with the Director, Regional Managers, System Operations, and Staff Development and Training, we’ll assure that leadership is aware of the release of the survey and the procedures in place for dispositioning the responses.

In order to continue to receive information about our efforts, we may release at least two surveys per year.

The survey will developed and released using SurveyMonkey and we will analyze responses to gather insight and drive change management. 

The PMO will release to project stakeholders and participants the results of the survey.  If additional user information is needed, another survey may be released, coordinated with DPA leadership.  We may also use methods as listed in the "Discovery Session Format" section above to collect the information.

As workers use the new feature, they will report any issues to DPA’s help desk. Systems operations will open a help desk ticket in Jira and assign the ticket to PMO reviewer.

Systems operations log any independently discovered issue into Jira, assigning to the PMO for review.

PMO will be responsible for documenting new features or changes into Azure DevOps, through assessment with leadership of information gathered in Help Desk tickets.

New features will be documented in Azure DevOps with information generated by:
- Worker Help Desk Tickets
- System Operations discovered issues
- Policy change
- Maintenance requirements

## Expectations
We expect:
- SME’s to be: 
  - Chosen and oriented before the work begins;
  - Available at appointed times.
- System Operations to:
  - Be integral to the testing process in Azure DevOps;
  - Record feature issues in JIRA HelpDesk with a PMO assignment for review;
  - Only record new issues.

## Challenges

- DPA workers other priorities may delay feedback gathering efforts;
- Supervisors must account for assignment of each workers daily schedule, so we must be careful to include Field staff leadership in all contact;
- DPA System Operations other priorities may delay testing efforts.
