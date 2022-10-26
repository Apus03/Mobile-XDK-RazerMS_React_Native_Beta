See the closing issue Via Merge Request https://docs.gitlab.com/ee/user/project/issues/closing_issues.html#via-merge-request

## What does this MR do?

(briefly describe what this MR is about)

### Relevant logs and/or screenshots

(Paste any relevant logs and/or screenshots - please use code blocks (```) to format console output, 
logs, and code as it's very hard to read otherwise.)

### Note for Deployer

(Write a message to deployer here if have)

----
#### Risk Analysis

Document: [INFORMATION RISK ASSESSMENT HANDBOOK](https://razermis.sharepoint.com/sites/RMSDocLib/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FRMSDocLib%2FShared%20Documents%2FRMS%20CENTRAL%20REPOSITORY%2FRMS%20IT%20%28%20RMS%2DIT%2Dxx%29%2FRMS%2DIT%2D006%20RMS%20IS%20Risk%20Management%2FRMS%20Information%20Risk%20Assessment%20Handbook%2Epdf&parent=%2Fsites%2FRMSDocLib%2FShared%20Documents%2FRMS%20CENTRAL%20REPOSITORY%2FRMS%20IT%20%28%20RMS%2DIT%2Dxx%29%2FRMS%2DIT%2D006%20RMS%20IS%20Risk%20Management)  
Formula: ```Risk Score = Asset Value X Impact X likelihood```

Asset Value: (Score value here - ```<Future Implementation>```)  
(List all the web page, functions or features that involve in this MR.)

Impact: (Score value here - ```<Future Implementation>```)   
(List down all the impact when something wrong happen on this changes or when this changes got bug/error. Write no impact if it not.)
+ Buyer :
+ Merchant:
+ RMS:
+ Bank/Processor:

Likelihood: (Score value here - ```<Future Implementation>```)  
(For the bug/incident type issue/merge request, mention here how frequent it happen. For others type issue/merge request, just write new implementation.)

- [ ] New implementation
- [ ] Rare - May only occur in exceptional circumstances; simple process; no previous incidence of non-compliance
- [ ] Unlikely - Could occur at some time; less than 25% chance of occurring; non-complex process &/or existence of checks and balances
- [ ] Possible - Might occur at some time; 25 – 50% chance of occurring; previous audits/reports indicate non-compliance; complex process with extensive checks & balances; impacting factors outside control of organization
- [ ] Likely - Will probably occur in most circumstances; 50-75% chance of occurring; complex process with some checks & balances; impacting factors outside control of organization
- [ ] Almost certain - Can be expected to occur in most circumstances; more than 75% chance of occurring; complex process with minimal checks & balances; impacting factors outside control of organization

Risk Score: (Score value here - ```<Future Implementation>```)

#### Merge Request Checklist [^1]

- [ ] My code follows the style guidelines of this project [^3]
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] My changes generate no new warnings
- [ ] **`I have added tests that prove my fix is effective or that my feature works`**
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules

#### Code Review Checklist [^2]

- [ ] Merge Request label has been define properly (DO, Type, Priority & Severity)
- [ ] Merge Request description have clear message
- [ ] An issue(s) has been pointed to this Merge Request and it approved
- [ ] Requested Merge is from **working branch** to **UAT branch**
- [ ] Latest log and/or screenshots has been attached
- [ ] **`Does the code work? Does it perform its intended function, the logic is correct etc.`**
- [ ] Required logs are present
- [ ] Adhere [OWASP Secure Coding Practices](https://owasp.org/www-pdf-archive/OWASP_SCP_Quick_Reference_Guide_v2.pdf)
- [ ] No sensitive information is logged or visible in a stacktrace
- [ ] Do test cases exist, and are they comprehensive?
- [ ] Do test cases actually test that the code is performing the intended functionality?

----

[^1]: This checklist fill up by **`Coder (Programmer/Developer)`**.
[^2]: This checklist fill up by **`Reviewer (Senior Developer/Team Lead)`**.
[^3]: [Software Engineer/Programmer SOP](https://docs.google.com/document/d/1UsOuxHYm8mYAuvHj7ZiNtnM_tpaA0mQ_lh_Cq6cpYJU/edit?usp=sharing).
