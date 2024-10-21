**As a** customer  
**I need** to reset my password if I forget it  
**So that** I can regain access to my account  

### Details and Assumptions
* The customer must provide a valid email address linked to their account
* A password reset link will be valid for 24 hours
* Users should receive confirmation after resetting their password 

### Acceptance Criteria
```gherkin
Given a customer has forgotten their password
When they request a password reset 
Then a reset link is sent to their registered email address
