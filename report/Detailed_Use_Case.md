# Detailed Use Case

## Selected Use Case : UC04

> As a contributor, I want to submit my material for publication, so that I can start a request and check its status

### 6.1 Header

| Field | Worked content |
|---|---|
| ID and name | UC-04 Submit Request|
| Scope | Digital Archive Contribution Service |
| Level | User goal |
| Primary actor | Contributor |
| Preconditions | The contributor is authenticated. An allocation is open to receive a request |
| Trigger | The contributor decides to submit material for publication. |
| Minimal guarantee | No incomplete request is recorded, and the contributor is told which required details are missing. |
| Success guarantee | A request with its items is recorded in the system, and the contributor is given a reference and a confirmation that it has been received. |
| Open issue | Whether a request can be submitted when no allocation is open, and what minimum information a request must contain before it is accepted (S7 Q1). |


### 6.2 Main Success Scenario

| Step | Actor intention or system responsibility |
|---|---|
| 1 | The contributor starts a new request for publication. |
| 2 | The system identifies the contributor and prompts to enter material details. |
| 3 | The contributor enters the required details and attaches the material.
| 4 | The system checks that each requirement details are complete|
| 5 | The system prompts user to confirm details |
| 6| The system checks that an allocation is open to receive the request  |
| 7 | The system records the request with its items and assigns an awaiting status to the request. |
| 8 | The system creates a unique reference for the request. |
| 9 | The system confirms to the contributor that the request has been received. |
| 10 | The contributor sees current status using unique request reference. |

### 6.3 Extensions

| Ref | Condition | Response and destination |
|---|---|---|
| 3a. | The contributor cancels before submitting | Discard the request; End; |
| 4a. | Required details are missing | Shows which required details are missing and why they are needed; Resume at step 3. |
| 5a. |  The contributor chooses to edit the details before confirming. | Return to step 3 to amend the details | 
| 6a. | No allocation is open to receive the request (depends on the open issue in 6.1). | Inform the contributor that no allocation is open, and record the request as queued with a priority; resume at step 7. |



### 6.4 Quick classification check

| Ref | Type |
|---|---|
| 3a | Cancellation extension |
| 4a | Recoverable extension |
| 5a | Recoverable extension |
| 6a | Recoverable extension (depends on the open issue in 6.1) |

**3a: Cancellation extension** - The contributor chooses to stop before the request is submitted, so the system has recorded nothing and the use case ends. It is a cancellation rather than a failure because no rule has refused the request; the contributor simply decides not to continue.

**4a: Recoverable extension** - The system’s completeness check finds that required details are missing, so it stops and tells the contributor which details to supply. Nothing is lost, and the flow returns to step 3, where the contributor enters the missing information and the check runs again.

**5a: Recoverable extension** - The contributor chooses to edit the details before confirming them. No rule is broken and nothing is recorded yet, so the flow simply returns to step 3 to amend the details and continue.

**6a: Recoverable extension , depending on the open issue.** - No allocation is open to receive the request. If queuing is in scope, the system records the request as queued and the flow continues at step 7, so nothing is lost. If queuing is out of scope, the same situation becomes a failure extension, because the use case would end with no request recorded.