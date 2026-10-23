# Checking grammer and improving language #

**Prompt**: I've completed my Step 1: "Extracting information about the current situation". Could you read through the "What the evidence tells" column and fix any grammar mistakes, as well as improving the language. Please highlight where the problem is as well

**Response:**

Revised "What the Evidence Tells Us" Column

I can't apply coloured highlighting in chat, so problems are marked in **bold** in the original text. The corrected version follows in the right-hand column. In Word, you can highlight the same words with the Highlight tool.

| Ref | Original, with problems in bold | Corrected |
|---|---|---|
| S1 L1 | The service handles **serval** media types from two kinds of contributors (Individuals & local organisations), so the service has to handle various files and sources. | The service handles several media types from two kinds of contributor (individuals and local organisations), so it has to handle a wide range of files and sources. |
| S1 L2 | Every part of a request is stored in different places. Establishing the full state of a request therefore means checking several locations **(missing full stop)** | Each part of a request is stored in a different place, so establishing the full state of a request means checking several locations. |
| S2 L1 | Contributions vary from having one item or many items, and change to one can affect the **reset** of the collection | Contributions range from a single item to many items, and a change to one item can affect the rest of the collection. |
| S2 L2 | **Ownership and authority of material submitted is** not always certain | The ownership and authority of submitted material are not always certain. |
| S2 L3 | There is **no single-entry point** for requests and submissions may be incomplete. Staff must chase missing information rather than receive complete requests. *(Overreach: the scenario says requests arrive through several channels, not that there is no entry point.)* | Requests arrive through several channels, so there is no single point of entry, and submissions may be incomplete. Staff must chase missing information rather than receive complete requests. |
| S2 L5 | Decisions about which requests come first **depends** on who handles them. Requests in the same situation may receive different outcomes, which **causes** fairness and audit risks. | Decisions about which requests come first depend on who handles them. Requests in the same situation may receive different outcomes, which creates fairness and audit risks. |
| S2 L6 | Third parties can be involved **with** a request | Third parties can be involved in a request. |
| S2 L7 | **There's uncertainty around staff in relation to authority** over requests which introduces risks and delays *(Overreach: the scenario doesn't confirm that delays occur.)* | Staff are uncertain about their authority over requests, which creates risk and may cause delays. |
| S3 L1 | Reviews are considered on multiple factors, so a request can fail on any one of the **several factors** | Reviews consider multiple factors, so a request can fail on any one of them. |
| S3 L2 | Keeping an item and publishing it are separate outcomes. The system must be able to hold **the material** that is not yet cleared for release **(missing full stop)** | Keeping an item and publishing it are separate outcomes. The service must be able to hold material that is not yet cleared for release. |
| S3 L3 | ...because of staffing, **recourses** or timing. A place can look free but still **may be** unusable... | ...because of staffing, resources or timing. A place can look free but still be unusable. |
| S3 L4 | A vacancy visible on screen cannot be used as a basis for allocation. The requirements must be checked separately **(missing full stop)** | A vacancy visible on screen cannot be used as the basis for allocation. Requirements must be checked separately. |
| S3 L5 | ...so capacity is tied up without progress. **The frequency is also not stated**, so the scale of this is unknown | ...so capacity is tied up without progress. The frequency is not stated, so the scale of the problem is unknown. |
| S3 L6 | One change can have **knock on** effects. | One change can have knock-on effects. |
| S4 L1 | **Progress is recorded informally**, and there is **no authoritative record** of where a request stands, which makes reporting unreliable. *(Overreach: "informally" is not in the scenario, and "no authoritative record" is an inference.)* | Progress is recorded in notes, messages and spreadsheets, with no clear authoritative record of where a request stands. This makes reporting unreliable. |
| S4 L2 | **. Different** teams use status terms differently... **Status terms are not standardized** across teams. Accountability is also lost in this gap | Different teams use status terms differently, which makes it difficult to see what is awaiting action and who is responsible. *(Stray full stop removed. "Standardised" is used to match British spelling elsewhere.)* |
| S4 L3 | ...so the record **shows what happened** | ...so the record accurately shows what actually happened. |
| S4 L5 | A review **does not necessarily mean an end of** a request. It can reopen the work, change earlier arrangements, or pass **that matter** to someone else | A review does not necessarily end a request. It can reopen the work, change earlier arrangements, or pass the matter to someone else. |
| S5 L4 | Staff may need to carry out some work off-site, where they may not have a reliable connection | No change needed. |
| S6 L3 | **Some allocations are being held without them being released or confirmed.** This leads to **the amount of places** available for **students** being decreased *(Students are not mentioned in the scenario.)* | Some allocations are held without being released or confirmed, which reduces the number of places available for new allocations. |

Please check two things before you submit. First, S2 L3 and S4 L1 contain inferences that the scenario doesn't state directly. Keep them only if you can justify them, or mark them as Implied. Second, S6 L3 should not mention students unless the original scenario says so, and it doesn't.

# Approach to creating table for step 2#

prompt: for step 2: "separate symptom, problems, and consquences", I have made my table with the follwoing columns : PR ID, REF, Observation or symptom, Underlying Problem, Likely consequence. Should I go through my scenario annotation and pick out the the highlighted "Current Problems" or use the previous table to pick out the problems?

Response:

Use both, but start from the Step 1 table.

The Step 1 table already gives you the observations, and each row has a Ref you can carry into your Step 2 REF column. That keeps the chain traceable: Step 1 evidence → Step 2 symptom → problem → consequence.

Then check your annotation's "Current Problem" tags against it. The tags tell you which problems you identified during annotation, so use them to catch any you missed in Step 1. Don't copy them straight across, though, because a Current Problem tag often mixes a symptom with its cause. For example, "making it difficult to identify what is awaiting action and who is responsible" (S4 L2) is a consequence, and the underlying problem is that status terms differ between teams.

A practical method:

1. Take each Step 1 row and write the observation as the symptom, in neutral terms.
2. Ask "why does this happen?" to get the underlying problem. This is often where you'll use the Current Problem tags.
3. Ask "what does this lead to?" to get the likely consequence, and mark it as Implied where the scenario doesn't state it.

Also check that every Current Problem tag in your annotation maps to a row. Any tag with no matching row either needs a new row or should be dropped.

# Checking Business Problem Statement #

**Prompt:** 
Step 3 - Business
Problem
.docx
17 lines
DOCX
Could you check over my Step 3: Business Problem Statement and improve the wording and provide any feedback on the structure

**Response:**

## Structure feedback

- **Lead with the overview.** The root-cause summary is the strongest point, but it sits at the end, so the reader meets the details before the big picture. Move it to the opening paragraph, then use the detail paragraphs to support it.
- **Group related points.** The paragraphs follow the order of the Step 2 rows, which is logical for your workings but not for a reader. Consider grouping them under three headings: information and records, intake and decisions, and capacity and access.
- **Name who is affected.** Staff, contributors, service users, managers and partners appear, but the statement never says who bears each risk. A short sentence on impact would help.
- **Use one term for capacity.** The draft moves between "capacity", "places" and "allocations". Choose one main term and define it once.
- **Decide on the S-references.** They show traceability, which is useful for marking. If your brief doesn't require them in the statement, keep them in a reference key or your Step 2 table instead.

## Wording and grammar

- "Kerry Community Digital archive" should use the same capitalisation as the full name: "Kerry Community Digital Archive".
- "slow staff down in searching" → "slow staff down when searching".
- "Ownerships" → "Ownership".
- "This as a result creates rights risks" → "This creates rights risks".
- "Requests therefore may be delayed" → "Requests may therefore be delayed".
- "may also work off-site where connectivity" → "may also work off-site, where connectivity".
- "block capacity to new requests" → "block capacity for new requests".
- "the record may not show what has happened" → "the record may not show what has actually happened".
- "Changes therefore may leave" → "Changes may therefore leave".
- "it's records" → "its records" (no apostrophe; this is a possessive).
- The connectivity paragraph has no full stop at the end.
  
  <br><br>

# Consdering alternative perspectives

Gave use cases to consider alterntive perspectives and potential gaps I might missed e.g. asking what some the quesitons revelaed would have been for uses cases

Helped me decide what other things to consider and if it was relevant.

Promt Used : What are some possible questions revealed about this use case "**### Selected User Story: US08**

\> As a staff member, I want to access records off-site when connectivity is unreliable, so that I can keep working on requests"

Answer: 

For US08, the main questions revealed relate to offline access, the tasks staff can perform without connectivity, data security, and how changes are saved and synchronised when the connection returns.

User story:

> As a staff member, I want to access records off-site when connectivity is unreliable, so that I can keep working on requests.

## Possible questions revealed

| Area                        | Questions to clarify                                                                                                                                                                   |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. Accessing records        | Which records should staff be able to access off-site? Can they access all records or only requests assigned to them? Must records be downloaded or synchronised before going offline? |
| 2. Offline functionality    | Can staff only view records, or can they also edit details, add notes and update request statuses while offline?                                                                       |
| 3. Data accuracy            | How can staff tell when a record was last updated? Should the system warn them when information may be out of date?                                                                    |
| 4. Security and permissions | How is sensitive information protected when stored on a device? What happens if a staff member's access permissions change while they are offline?                                     |
| 5. Synchronisation          | What happens when connectivity returns? Are offline changes synchronised automatically? How are conflicting changes handled if another staff member has updated the same record?       |

## Five key questions to prioritise

1. Which records need to be available offline? All records, assigned requests only, or selected records downloaded in advance?
2. What tasks must staff be able to perform without connectivity? Viewing records, editing requests, adding notes, or changing statuses?
3. How will the system protect sensitive information on devices used off-site?
4. How will changes made offline be saved and synchronised when connectivity returns?
5. What happens if two staff members make conflicting changes to the same request?

## Additional scenarios to consider

- What happens if the device loses connectivity while a staff member is editing a record?
- Can staff see which changes have been saved locally and which have synchronised successfully?
- What happens if the device runs out of storage while offline?
- How long should records remain accessible without synchronisation?
- Can staff continue working if connectivity repeatedly drops in and out?


<br><br>
# Find the Objects

## Promt 1: 

Finding_The_Objects.md
can you make a table for Task 2 with headings "Candidate, Classification, Reason" For each Section in Task 1 and put the values from Candidate terms in Task 1 tables into Task 2 table column "Candidate". Also leave Classification and Reason columns blank

Response:

### Task 2: Classify the candidates



#### Organisation and current service

| Candidate | Classification | Reason |
|---|---|---|
| Kerry Community Digital Archive | | |
| Receives | | |
| Photographs | | |
| Documents | | |
| Audio | | |
| Video | | |
| Contributed | | |
| Individuals | | |
| Local Organisations | | |
| Submission Files | | |
| Descriptions | | |
| Ownerships statements | | |
| Permissions | | |
| Review Notes | | |
| Publication Decisions | | |
| Stored | | |
| Forms | | |
| Folders | | |
| Spreadsheets | | |

#### Requests, eligibility and preparation

| Candidate | Classification | Reason |
|---|---|---|
| Contribution | | |
| Item | | |
| Related Collection | | |
| Contributor | | |
| Material | | |
| Rights Holder | | |
| Ownership | | |
| Permissions | | |
| Requests | | |
| Channels | | |
| Incomplete | | |
| Staff | | |
| Expression | | |
| Awaiting | | |
| Evidence | | |
| Decision | | |
| Priorities | | |
| Exceptions | | |
| Applied | | |
| Person or Organisation | | |
| Assist | | |
| Authority | | |
| Required | | |
| Detailed Information | | |
| Sharded | | |

#### Allocation and coordination

| Candidate | Classification | Reason |
|---|---|---|
| Review | | |
| Considers | | |
| File Quality | | |
| Description | | |
| Sensitivity | | |
| Ownership evidence | | |
| Access Restrictions | | |
| Relevance | | |
| Item | | |
| Preserved | | |
| Approved | | |
| Public Access | | |
| Capacity | | |
| Depends On | | |
| People | | |
| Places | | |
| Resources | | |
| Timing | | |
| Visible Vacancy | | |
| Requirement | | |
| Satisfied | | |
| Provisional Allocations | | |
| Remain | | |
| Essential information | | |
| Missing | | |
| Changes | | |
| Affect | | |
| Linked Arrangements | | |
| Staff | | |
| Preserve | | |
| Confirmed Position | | |
| Earlier Evidence | | |
| Versions | | |

#### Progress, review and exceptions

| Candidate | Classification | Reason |
|---|---|---|
| Staff | | |
| Progress | | |
| Decisions | | |
| Outstanding Actions | | |
| Notes | | |
| Messages | | |
| Spreadsheets | | |
| Teams | | |
| Status Terms | | |
| Awaiting Action | | |
| Responsible | | |
| Planned Activity | | |
| Changed | | |
| Partially Complete | | |
| Paused | | |
| Withdrawn | | |
| Distinguish | | |
| Operational Change | | |
| Formal Decision | | |
| Silence | | |
| Approval | | |
| Reviews | | |
| Generate | | |
| New Actions | | |
| Revised Arrangements | | |
| Escalation | | |
| Earlier Evidence | | |
| Overwritten | | |
| Circumstances Change | | |

#### Information, reporting and scope

| Candidate | Classification | Reason |
|---|---|---|
| Coordinator | | |
| Needs | | |
| Information | | |
| Unallocated Requests | | |
| Provisional Arrangements | | |
| Capacity Conflicts | | |
| Overdue Actions | | |
| Incomplete Records | | |
| External Partners | | |
| Receive | | |
| Role | | |
| Summary Reporting | | |
| Needed | | |
| Management | | |
| Funders | | |
| Exposing | | |
| Unnecessary | | |
| Personal or commercially sensitive information | | |
| Connectivity | | |
| Unreliable | | |
| off-site Work | | |
| Initial Scope | | |
| Service Coordination | | |
| Records | | |
| Specialist Professional Systems | | |
| Financial Accounting | | |
| Unrelated Public Website Functions | | |
| Outside Scope | | |

#### Stakeholder evidence

| Candidate | Classification | Reason |
|---|---|---|
| Coordinator | | |
| Vacancy | | |
| Match | | |
| Important Requirements | | |
| Satisfied | | |
| Service User | | |
| Need | | |
| Waiting for information | | |
| Decision | | |
| Outside Organsation | | |
| Administrator | | |
| Provisional Arrangements | | |
| Capacity | | |
| Request | | |
| Stalled | | |
| Partner Representatives | | |
| Role | | |
| Case History | | |
| Reviewer | | |
| New Information | | |
| Added | | |
| Erasing | | |
| Earlier Decisions | | |
| Manager | | |
| Reasons for delay | | |
| Withdrawal | | |
| Incomplete Outcomes | | |

#### Unresolved matters

| Candidate | Classification | Reason |
|---|---|---|
| Information is required | | |
| Request | | |
| Ready for decision | | |
| Eligibility | | |
| Priority | | |
| Exceptions | | |
| Applied | | |
| Authority | | |
| Acts for requester | | |
| Provisional Allocations | | |
| Expire | | |
| Confirmed | | |
| Approve Changes | | |
| Substitutions | | |
| Withdrawal | | |
| Versions | | |
| Reviews | | |
| Outstanding Actions | | |
| Staff | | |
| Partners | | |
| Funders | | |
| Shared | | |

## prompt 2

"can you convert this classification guide from the lab into markdown "Classification guide
Classification

Question

Examples

Conceptual class

Does the domain need to remember identity, facts, relationships or lifecycle?

Student, Activity, Registration

Attribute or value

Is it a simple descriptive value of another concept?

capacity, status, sessionDate

Actor

Does the external role interact with the system boundary?

Student, Organiser, Manager

Operation or event

Is it an action that may reveal a transaction concept?

register, cancel, attend

Out of scope / implementation

Is it a screen, database, framework, service layer or unsupported detail?

form, table, controller"

Answer:
### Classification Guide

| Classification | Question | Examples |
|---|---|---|
| Conceptual class | Does the domain need to remember identity, facts, relationships or lifecycle? | Student, Activity, Registration |
| Attribute or value | Is it a simple descriptive value of another concept? | capacity, status, sessionDate |
| Actor | Does the external role interact with the system boundary? | Student, Organiser, Manager |
| Operation or event | Is it an action that may reveal a transaction concept? | register, cancel, attend |
| Out of scope / implementation | Is it a screen, database, framework, service layer or unsupported detail? | form, table, controller |

## Promt 2 : 
"How could I color the actions column for in the refined list section in markdown?"

Response: 
## Colouring the Action column

Standard markdown has no colour. Text colour needs HTML, and many viewers ignore it. Here are the options from most to least reliable.

### 1. Coloured emoji (works almost everywhere)

Use a symbol in the Action column:

- 🟢 Keep
- 🟡 Merge
- 🔵 Convert
- 🔴 Remove

For example: `🟢 Keep`, `🔴 Remove`.

This is the safest option, because the colour is visible and the word is still there for screen readers and for copying into Word.

### 2. HTML colour span (works in some viewers, not GitHub or most chat apps)

```html
<span style="color:green">Keep</span>
<span style="color:orange">Merge</span>
<span style="color:blue">Convert</span>
<span style="color:red">Remove</span>
```

Inside a table, this only works if the viewer allows inline HTML. Many don't, so the text may show literally as tags.

### 3. Use colour in Word or Excel instead

If the final submission is a Word document or spreadsheet, colour the cells there. Word can shade table cells, and Excel supports conditional formatting. Keep the markdown for drafting and apply colour when you format the final file.

I'd use option 1 for your working file, and option 3 for the submitted version, since your assessor will almost certainly open a Word or PDF document, not a markdown file.

## prompt 3 : 
"Could you give me a table for  each section for task 3. Insert values for candidate from task 2 section tables. Leave action, Final term, and reason blank"

Response: 

## Task 3: Refine the candidate list

### Organisation and current service

| Candidate | Action | Final term | Reason |
|---|---|---|---|
| Kerry Community Digital Archive | | | |
| Receives | | | |
| Photographs | | | |
| Documents | | | |
| Audio | | | |
| Video | | | |
| Contributed | | | |
| Individuals | | | |
| Local Organisations | | | |
| Submission Files | | | |
| Descriptions | | | |
| Ownerships statements | | | |
| Permissions | | | |
| Review Notes | | | |
| Publication Decisions | | | |
| Stored | | | |
| Forms | | | |
| Folders | | | |
| Spreadsheets | | | |

### Requests, eligibility and preparation

| Candidate | Action | Final term | Reason |
|---|---|---|---|
| Contribution | | | |
| Item | | | |
| Related Collection | | | |
| Contributor | | | |
| Material | | | |
| Rights Holder | | | |
| Ownership | | | |
| Permissions | | | |
| Requests | | | |
| Channels | | | |
| Incomplete | | | |
| Staff | | | |
| Expression | | | |
| Awaiting | | | |
| Evidence | | | |
| Decision | | | |
| Priorities | | | |
| Exceptions | | | |
| Applied | | | |
| Person or Organisation | | | |
| Assist | | | |
| Authority | | | |
| Required | | | |
| Detailed Information | | | |
| Sharded | | | |

### Allocation and coordination

| Candidate | Action | Final term | Reason |
|---|---|---|---|
| Review | | | |
| Considers | | | |
| File Quality | | | |
| Description | | | |
| Sensitivity | | | |
| Ownership evidence | | | |
| Access Restrictions | | | |
| Relevance | | | |
| Item | | | |
| Preserved | | | |
| Approved | | | |
| Public Access | | | |
| Capacity | | | |
| Depends On | | | |
| People | | | |
| Places | | | |
| Resources | | | |
| Timing | | | |
| Visible Vacancy | | | |
| Requirement | | | |
| Satisfied | | | |
| Provisional Allocations | | | |
| Remain | | | |
| Essential information | | | |
| Missing | | | |
| Changes | | | |
| Affect | | | |
| Linked Arrangements | | | |
| Staff | | | |
| Preserve | | | |
| Confirmed Position | | | |
| Earlier Evidence | | | |
| Versions | | | |

### Progress, review and exceptions

| Candidate | Action | Final term | Reason |
|---|---|---|---|
| Staff | | | |
| Progress | | | |
| Decisions | | | |
| Outstanding Actions | | | |
| Notes | | | |
| Messages | | | |
| Spreadsheets | | | |
| Teams | | | |
| Status Terms | | | |
| Awaiting Action | | | |
| Responsible | | | |
| Planned Activity | | | |
| Changed | | | |
| Partially Complete | | | |
| Paused | | | |
| Withdrawn | | | |
| Distinguish | | | |
| Operational Change | | | |
| Formal Decision | | | |
| Silence | | | |
| Approval | | | |
| Reviews | | | |
| Generate | | | |
| New Actions | | | |
| Revised Arrangements | | | |
| Escalation | | | |
| Earlier Evidence | | | |
| Overwritten | | | |
| Circumstances Change | | | |

### Information, reporting and scope

| Candidate | Action | Final term | Reason |
|---|---|---|---|
| Coordinator | | | |
| Needs | | | |
| Information | | | |
| Unallocated Requests | | | |
| Provisional Arrangements | | | |
| Capacity Conflicts | | | |
| Overdue Actions | | | |
| Incomplete Records | | | |
| External Partners | | | |
| Receive | | | |
| Role | | | |
| Summary Reporting | | | |
| Needed | | | |
| Management | | | |
| Funders | | | |
| Exposing | | | |
| Unnecessary | | | |
| Personal or commercially sensitive information | | | |
| Connectivity | | | |
| Unreliable | | | |
| off-site Work | | | |
| Initial Scope | | | |
| Service Coordination | | | |
| Records | | | |
| Specialist Professional Systems | | | |
| Financial Accounting | | | |
| Unrelated Public Website Functions | | | |
| Outside Scope | | | |

### Stakeholder evidence

| Candidate | Action | Final term | Reason |
|---|---|---|---|
| Coordinator | | | |
| Vacancy | | | |
| Match | | | |
| Important Requirements | | | |
| Satisfied | | | |
| Service User | | | |
| Need | | | |
| Waiting for information | | | |
| Decision | | | |
| Outside Organsation | | | |
| Administrator | | | |
| Provisional Arrangements | | | |
| Capacity | | | |
| Request | | | |
| Stalled | | | |
| Partner Representatives | | | |
| Role | | | |
| Case History | | | |
| Reviewer | | | |
| New Information | | | |
| Added | | | |
| Erasing | | | |
| Earlier Decisions | | | |
| Manager | | | |
| Reasons for delay | | | |
| Withdrawal | | | |
| Incomplete Outcomes | | | |

### Unresolved matters

| Candidate | Action | Final term | Reason |
|---|---|---|---|
| Information is required | | | |
| Request | | | |
| Ready for decision | | | |
| Eligibility | | | |
| Priority | | | |
| Exceptions | | | |
| Applied | | | |
| Authority | | | |
| Acts for requester | | | |
| Provisional Allocations | | | |
| Expire | | | |
| Confirmed | | | |
| Approve Changes | | | |
| Substitutions | | | |
| Withdrawal | | | |
| Versions | | | |
| Reviews | | | |
| Outstanding Actions | | | |
| Staff | | | |
| Partners | | | |
| Funders | | | |
| Shared | | | |


# Summary

In summary I used claude for generating most of my tables for the CA which saved lots of time. I also want to be transparent about the fact that for each step of the project, I came up with the ideas / interpretation myself and then pasted my entire sections into claude. By doing so Claude helped to keep traceability of facts between sections which I used as a guide to help write sections.

For example in "Stakeholders and Requirements Analysis" for my "Separate Symptoms, Problems, and Consequences" section, I created the full table myself and added references to the problems from the scenario. I then pasted my finished table into Claude, which helped highlight other lines in the scenario that could be referenced for each problem.

 However it was still my decision to accept or reject the suggestions based on if I felt they were relevant or not. This was necessary as sometimes claude would suggest a reference to include, and I would create an argument for whether it was or was not needed, and Claude would change its answer.

For example it suggested a reference to include, I argued it wasn't relevant because of such a reason and it would change it answer from: Yes it needed to Yes your correct that it isn't needed

Claude also helped clean up language, which can be seen throughout the project. I would finish my tables, past them into claude and it would reword my sentences without adding to them, helping me communicate my ideas more clearly. This improved my workflow as sometimes I would jot down ideas for a sentence and it would generate a correct structured sentence based from the ideas I noted down.



