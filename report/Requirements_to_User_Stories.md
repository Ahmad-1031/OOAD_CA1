
# From Requirements to User Stories

## Supplied Requirements

| ID | Functional Requirement | Priority | Source |
|---|---|---|---|
| FR01 | The system shall allow staff to view information about a contribution through a single record. | Should | Staff (SKH3), INS1 |
| FR02 | The system shall allow a contributor to view rights and permissions confirmation of submitted material. | Should | Contributor (SKH1), INS2 |
| FR03 | The system shall allow staff to verify third party authorisation before a request's information is disclosed | Must | Staff (SKH3), INS3 |
| FR04 | The system shall allow a contributor to submit a request through a single point of entry for publication. | Must | Contributor (SKH1), INS4, INS9 |
| FR05 | The system shall allow staff to apply priorities and exceptions to requests. | Must | Staff (SKH3), INS5 |
| FR06 | The system shall allow an administrator to view blocked capacity and release stalled requests. | Should | Administrator (SKH8), INS6 |
| FR07 | The system shall allow reviewers to view dependencies between linked arrangements. | Could | Reviewer (SKH9), INS7 |
| FR08 | The system shall allow staff to access records off-site when connectivity is unreliable. | Should | Staff (SKH3), INS8 |
| FR09 | The system shall allow third parties to assist with the processing of requests. | Must | Third parties (SKH7), INS3 |
| FR10 | The system shall allow staff to set an activity status on a request from the agreed standard terms. | Must | Staff (SKH3), INS9 |
| FR11 | The system shall allow staff to send external partners only the information required for their role. | Must | Staff (SKH3), External partners (SKH4), INS3 |
| FR12 | The system shall show coordinators unallocated requests, provisional allocations, capacity conflicts, overdue actions and incomplete records. | Must | Coordinator (SKH2), INS1, INS6 |


## Task 1: Develop User Stories

| Story ID | Requirement | Role-Goal-Benefit user story|
|---|---|---|
|US01|FR01|As a staff member, I want to view information about a contribution through a single shared record, so I do not have to search across separate records
|US02|FR02|As a contributor, I want to view rights and permissions of my submitted material to ensure they are correct
|US03|FR03|As a staff member, I want to record the authority of reach request before third parties are involved, so that they are only involved with the right authority in place
|US04|FR04|As a contributor, I want to submit my material for publication through a single point of entry, so that I can start a request that the archive can review
|US05|FR05|As a staff member, I want to apply the agreed priorities and exceptions to requests, so that requests are handled fairly and consistently
|US06|FR06|As an administrator, I want to view blocked capacity and release stalled requests, so that the capacity for new requests is increased
|US07|FR07|As a reviewer, I want to view the dependencies between linked arrangements, so that I can see what effect changes have on other arrangements
|US08|FR08| As a staff member, I want to access records off-site when connectivity is unreliable, so that I can keep working on requests
|US09|FR09|As a third party, I want to view only the information my role requires about a request, so that I can assist with the processing of that request
|US10|FR10|As a staff member, I want to set the activity status of request using the agreed standard terms, so that the current status of the request is visible to everyone working on it
|US11|FR11|As a staff member, I want to send external partners only the information required by their role, so that they receive what they need without unnecessary case history
|US12|FR12|As a coordinator, I want to view unallocated requests, provisional allocations, capacity conflicts, overdue actions and incomplete records, so that I can coordinate requests and capacity

<br>

## Task 2: Acceptance Criteria

### Selected User Story: US01

> As a staff member, I want to view information about a contribution through a single shared record, so I do not have to search across separate records

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
|A1 |The staff member is authenticated before viewing the record |
|A2 |Searching for a contribution returns only one record|
|A3 |The record shows the current status, review stage, and ownership status of the contribution|
|A4 |An update made by one staff member is visible to other staff members viewing the same record|
|A5|Earlier versions of the record remain visible when new information is added|
|A6|A staff member can find all the information about a contribution without opening any other record|

#### Given When Then

```gherkin
Given a contribution has been submitted
And and the contribution has a current activity status, review stage, and ownership recorded
When an authenticated staff member viws the contribution's record
Then the record shows the current activity status
And the record shows reviw stage
And the record shows the ownership status
```

#### Questions Revealed

1. Which staff member can view and edit the record
2. What is the minimum information required for a contribution before it's accepted and viewable in the system
3. Can a contribution be viewed before it has been allocated?
4. How much history is shown for the record, and is older history archived after a certain period?

<br><br>

### Selected User Story: US002
> As a contributor, I want to view rights and permissions of my submitted material to ensure they are correct

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
|A1 |The contributor is authenticated before viewing rights and permissions |
|A2|Each contribution by the contributor has rights and permissions recorded in the system|
|A3| The contributor can see the rights and permissions of each item they have submitted|
|A4|When a staff member updates an item's rights and permissions, the contributor can see the updated changes|
|A5| The contributor cannot see the rights and permissions of material submitted by another contributor|


#### Given When Then

```gherkin
Given the contributor is authenticated
And the contribution exists in the system
And the contribution has rights and permissions recorded
When a contributor views their contribution
Then the rights and permissions of their contribution are shown
And the rights and permissions of other contrbutors material are now shown
```

#### Questions Revealed

1. Can a contributor see the full rights and permissions record? or only a summary of it?
2. If the contributor thinks the rights or permissions are wrong, how do they raise a correction, and who handles it?
3. Should a contributor see internal staff notes that explain why a right status was set
4. Can a contributor see rights and permissions for material they co-own with another contributor, or only for items where they are the sole owner?

<br><br>

### Selected User Story: US03

>  The system shall allow staff to record authority for each request before third parties are involved.

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US04

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US05

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US06

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US07

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US08

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US09

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US10

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US11

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>

### Selected User Story: US12

> Example user story

#### Acceptance Criteria

| ID | Observable acceptance condition |
|---|---|
| | |

#### Given When Then

```gherkin
Given
When
Then
```






#### Questions Revealed

1.
2.
3.

<br><br>


## Task 3: Identify Actors and Use Cases

### Actor Decisions

## Use-Case Catalogue

| Use Case | Primary Actor | Meaningful Outcome | Source Requirement |
|---|---|---|---|
| | | | |

## Task 4: Use-Case Diagram

## Task 5: Traceability

| Business problem or stakeholder goal | Requirement | User Story | Acceptance Evidence | Use Case |
|---|---|---|---|---|
| | | | | |