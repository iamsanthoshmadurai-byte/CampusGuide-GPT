# Custom GPT Use Case Document

## Project Title

College Student Help Assistant

## 1\. Real-World Problem Identification

### Potential Problems Considered

|Potential problem|Frequency|Knowledge-based|Clear scope|GPT suitability|Required information available|
|-|-|-|-|-|-|
|Students repeatedly ask about college rules, deadlines, facilities, and procedures|High|Yes|Yes|Yes|Can be documented from approved college information|
|Students ask for help finding study resources and understanding course topics|High|Partly|Yes|Yes|Syllabi and approved learning resources can be collected|
|Students ask for attendance corrections or changes to official records|Medium|No; often requires action and verification|Yes|Low|Requires access to official systems and staff approval|

### Selected Problem

Students repeatedly ask the college office or class representatives the same general questions about college rules, academic dates, facilities, and routine procedures. Answers may be spread across notices, handbooks, and web pages. This can cause delays, repeated work for staff, and confusion when students cannot find the latest approved information.

This is a suitable Custom GPT use case because the questions are repetitive, knowledge-based, and can be answered conversationally using approved reference documents. The GPT will provide guidance, not make official decisions or change student records.

## 2\. GPT Name

### Name Ideas

1. CampusGuide GPT
2. College Help Desk
3. Student Support Assistant
4. Campus Companion
5. UniInfo Assistant

### Selected Name

**CampusGuide GPT**

The name is short, clear, and tells users that the assistant helps them find campus information.

## 3\. Target Users

### Primary Users

* Current college students who need quick answers about routine college information.
* New students who need help understanding campus services and procedures.

### Secondary Users

* Faculty members and class representatives who receive repeated general questions.
* Administrative or student-support staff who maintain the approved information used by the assistant.

## 4\. Problem Statement

Students frequently need information about college rules, academic dates, campus facilities, and routine procedures. This information may be distributed across notices, handbooks, and different college pages, so students may not know where to look or whether they have found the latest version. Staff and class representatives then spend time answering the same questions repeatedly.

CampusGuide GPT will provide a conversational way to find and understand approved college information. It will answer from the supplied documents, explain procedures in simple language, and direct users to the relevant official source when possible. If the information is missing, unclear, or potentially out of date, it will say so and recommend contacting the appropriate college office rather than inventing an answer.

## 5\. Proposed Solution and Scope

### Included in the First Version

* Answer frequently asked questions using approved college documents.
* Explain published rules and procedures in simple language.
* Help users locate information about academic dates, facilities, student services, and general policies.
* Identify the source document or official contact when available.
* Ask a clarifying question when a request is ambiguous.
* State clearly when an answer cannot be verified from the supplied information.

### Not Included in the First Version

* Changing attendance, grades, fees, or other official records.
* Approving leave, scholarships, exemptions, or other applications.
* Giving access to private student records.
* Replacing official announcements or decisions made by college staff.
* Providing guaranteed answers when no approved source is available.

## 6\. Expected Outcomes and Success Measures

The following are proposed targets for a pilot. They are goals to measure, not results already achieved.

|Measure|Pilot target|How it will be measured|
|-|-|-|
|Answer usefulness|At least 80% of test questions receive a useful answer|Review a test set of at least 20 common questions|
|Source grounding|At least 90% of factual answers in the test set match an approved source|Compare answers with the source documents|
|Handling missing information|100% of deliberately unanswerable test questions are acknowledged as unknown or referred to staff|Test questions whose answers are absent from the documents|
|Ease of use|At least 4 out of 5 average user rating|Collect feedback from a small student pilot group|
|Reduced repeated enquiries|Aim for a 20% reduction in repeated basic enquiries during the pilot|Compare counts before and during the pilot, if the college can collect them|

## 7\. Information Required

The assistant will need current, approved, non-sensitive information such as:

* Student handbook and published college rules.
* Academic calendar and published deadline notices.
* Department and office contact details.
* Library, laboratory, transport, and other campus facility information.
* Published student-service procedures and frequently asked questions.
* Document titles, publication dates, and official source links where available.

Information owners should review documents before they are added. Outdated versions should be removed or clearly marked. Private student records, passwords, credentials, and confidential information must not be uploaded.

## 8\. Practicality and Feasibility

### Technical Feasibility

A first version is practical because it can be built around a Custom GPT and a small set of approved documents. It does not need to connect to student databases or perform transactions.

### Operational Feasibility

A college staff member or other authorized information owner must supply and periodically review the documents. A clear escalation contact is needed for questions that the assistant cannot answer.

### Main Risks and Controls

|Risk|Control|
|-|-|
|The assistant gives an incorrect or outdated answer|Use approved current documents, test common questions, show sources when possible, and say when unsure|
|Users treat an answer as an official decision|State that official decisions remain with the college and direct users to the responsible office|
|Sensitive information is exposed|Use only approved non-sensitive documents and follow organizational data policies|
|A question is outside the assistant's scope|Explain the limitation and refer the user to the appropriate office|

## 9\. Validation Plan

Before a pilot:

1. Collect and review the approved reference documents.
2. Prepare at least 20 common questions and their verified answers.
3. Test whether CampusGuide GPT answers from the documents accurately.
4. Include questions whose answers are missing to check that the GPT does not guess.
5. Ask a small group of users to rate clarity and usefulness.
6. Fix weak answers and repeat the test before wider use.

## 10\. Data Safety Note

Only fictional or non-sensitive examples should be used during development and testing. Do not enter confidential company or college information, passwords, credentials, personal information, customer information, or student records into an AI assistant unless the organization’s policies explicitly allow it. Use approved documents and follow the college's data-handling policies.

## 11\. Readiness Decision for Topic 2

**Decision: Ready to proceed to Topic 2, subject to obtaining approved source documents.**

Reasons:

* The selected problem is specific and recurring.
* Most questions are knowledge-based.
* A conversational GPT can provide value.
* The first version has a manageable scope and does not require access to private systems.
* Expected outcomes and a validation plan have been defined.
* The required information can be documented and reviewed.

### Readiness Checklist

* \[x] Identified 2–3 potential problems.
* \[x] Compared the potential problems.
* \[x] Selected one problem.
* \[x] Defined target users.
* \[x] Wrote the problem statement.
* \[x] Defined measurable expected outcomes.
* \[x] Listed the information required.
* \[x] Considered practicality, feasibility, and risks.
* \[x] Created this `use\_case\_document.md` file.
* \[ ] Collect and approve the actual college reference documents before building the GPT.

