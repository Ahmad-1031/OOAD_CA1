## Functional Requirements

| ID | Functional Requirement | Priority | Source |
|---|---|---|---|
| FR01 | The system shall allow staff to view information about a contribution through a single record. | Should | Staff (SKH3), INS1 |
| FR02 | The system shall allow a contributor to view rights and permissions confirmation of submitted material. | Should |S Contributor (SKH1), INS2 |
| FR03 | The system shall allow staff to verify third party authorisation before a request's information is disclosed. | Must | Staff (SKH3), INS3 |
| FR04 | The system shall allow a contributor to submit a request through a single point of entry for publication and track its status. | Must | Contributor (SKH1), INS4, INS9 |
| FR05 | The system shall allow staff to apply priorities and exceptions to requests. | Must | Staff (SKH3), INS5 |
| FR06 | The system shall allow an administrator to view blocked capacity and release stalled requests. | Should | Administrator (SKH8), INS6 |
| FR07 | The system shall allow reviewers to view dependencies between linked arrangements. | Could | Reviewer (SKH9), INS7 |
| FR08 | The system shall allow staff to access records off-site when connectivity is unreliable. | Should | Staff (SKH3), INS8 |
| FR09 | The system shall allow staff to preserve an item in the archive without approving it for public access | Must | Staff (SKH3), INS1 |
| FR10 | The system shall allow staff to set an activity status on a request from the agreed standard terms. | Must | Staff (SKH3), INS9 |
| FR11 | The system shall allow staff to send external partners only the information required for their role. | Must | Staff (SKH3), External partners (SKH4), INS3 |
| FR12 | The system shall show coordinators unallocated requests, provisional allocations, capacity conflicts, overdue actions and incomplete records. | Must | Coordinator (SKH2), INS1, INS6 |

## Non-Functional Requirements

| ID | Quality Type | NFR | Measure | Ref |
|---|---|---|---|---|
| NFR01 | Integrity | The system shall retain earlier versions of a record when it is changed, rather than overwriting them. | Versions retained. Period to be agreed. | S3 L7 |
| NFR02 | Security | The system shall restrict each user's view of records to the information their role requires. | Access by role. Permitted fields to be agreed. | S5 L2 |
| NFR03 | Privacy | The system shall exclude personal and commercially sensitive information from summary reports. | No sensitive fields in reports. Field list to be agreed. | S5 L3 |
| NFR04 | Reliability | The system shall allow staff to view and update records off-site without a continuous connection. | Full access offline. Sync time to be agreed. | S5 L4 |