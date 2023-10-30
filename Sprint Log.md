# Sprint 91
---
- public pending work: 
    * ABD Census Transformation
    * ABD Create Consolidated Reports
    * ABD WorkReport new portal

## Mason:
- [10/25/2023 - DONE] ONEDT: talk with Katrina on saving calculation(baseline AHT and actual AHT)
- [10/26/2023 - DONE] ONEDT: talk with Nancy to find more opportunity
- [10/25/2023 - DONE] CREST follow up
- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template
- [10/25/2023 - 10/26/2023] debug on THH CNA "Failed to establish connection to file storage server"
- [10/27/2023 - DONE] create parent case JS 
- Maintain JS [10/27/2023 - 10/26/2023]
    - [10/30/2023] principle ADDRESS REMOVE #
    - [10/30/2023] Guardian DOH SELECT & PHONE
    - DeltaAllied re-design due to website upgrade
    - MOO - occupation

- replace on EXLEL USERFACE with HTML

## Rain:
- [10/26/2023 - 10/30/2023] HWS policy checking compare location 
- [10/25/2023 - DONE] HWS policy checking compare VEH (TEST WITH BILLING AUDIT CODE)
- [10/27/2023 - DONE] M3 150 VEH compare


## Chloe:
- OPEX update: log the bug ratio (# of audit / # of bug)
    - [10/24/2023 - DONE] cannot match
    - [10/26/2023 - DONE] date validation for 1 day trainee 
    - [10/26/2023 - DONE] email wording, Data tab have value but email says no data generated

- Billing Audit
    * [10/25/2023 - DONE] compare when special split rule
    * [10/25/2023 - DONE] change clearcontents to delete row
    * [10/25/2023 - DONE] [button logic on platform. remove popup window](https://jira.rspinternal.com/browse/PAI-8805)
    * [10/25/2023 - DONE] re-write merge name function
    * [10/26/2023 - DONE] highlight dup name function
    * [10/27/2023 - DONE] optimize code
    * [pending optimize](https://rspproduct.atlassian.net/browse/PAI-8860)
     
- ABD WorkReport (Macro)[1.5w]
    - audit report with previous month
        * [10/20/2023 - 10/30/2023] [Compare Downloaded Report](https://jira.rspinternal.com/browse/PAI-8726)
            1. [10/27/2023 - DONE] a genearl workframe
            2. [10/30/2023] audit 2 report file
            3. log discrepancy
 
- GDP upload to BP REPLACE WITH PAD
    * book observation with GDP team to observe upload process daily report
    * move WA code to PAD and test

## June:
- ABD WorkReport (UiPath)
    1. login Websit(error handle for password expire notice)
        *  login with MFA
    2. generate 3 kind of report and download report, Save to filetodcs
        * [10/25/2023 - 10/26/2023 - DONE] download Termination report
        * [10/24/2023 - 10/25/2023 - DONE] download Employee Enrollments Comparison report
        * [10/24/2023 - DONE] navigate issue: cannot navigate after click button
        * [10/30/2023] SIT the bot
        
        
- Billing Audit
    - [10/26/2023 - DONE] mark the discrepancy's orignal source
    * [pending optimize](https://rspproduct.atlassian.net/browse/PAI-8861)

 - FPI	TTYD Reporting

 - Admin task - ONED run performance report and get AHT&ACC for each EE, summarize team performace



# Sprint 90
---
## Mason:
- [10/11/2023 - DONE] (EN & EASE done, GOCO [1/2])  ONEDT:  EASE  , GOCO portal - 2/3 EE extraction (dept extraction pending)
- [10/11/2023 - DONE] GDP - JS Code update due to website change (isolved)
- [10/12/2023 - DONE] GDP - iSolved: SIT & deploy JS Code 
- [10/12/2023 - DONE] GDP - Selerix Dept extraction: SIT & deploy JS Code 
- [10/12/2023 - DONE] CREST: JS notification email send to team
- [10/12/2023 - DONE] ASSA: deploy CNA for ASSA
- [10/16/2023 - 10/17/2023 - DONE] GDP - CENCUS AUDIT observation
- [10/17/2023 - DONE] GDP - CENCUS AUDIT 
- [10/17/2023 - DONE] GDP - temp -Jenny's CENCUS compare with PDF Invoice
- [10/18/2023 - DONE] GDP - revise Teladoc download method, added a group list to read config to replace download all
- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template


## Rain:
- [10/11/2023-10/12/2023 - DONE] HWS macro update: task assignment
- [10/11/2023 - DONE] M3 script update
- [10/12/2023 - DONE] M3 communicate shared folder
- [10/11/2023 - DONE] AAD script update
- [10/16/2023 - DONE] Observe HWS policy checking compare location & compare VEH
- [10/18/2023 - 10/19/2023 - DONE] AAD Decison workflow
- [10/19/2023 - DONE] AAD 4 uipath workflow on handle verification code
- [10/24/2023] HWS policy checking compare location & compare VEH

### Rain's PENDIGN TASKS
- HWS Renewal task UIautomation [2w]
- [10/12/2023 Holding]ABD CREAT SPD (JS) - holding due to 1
    1. low volume, low ROI
    2. pending confirm with team
- [10/13/2023 HOLDING] HWS - Download Documents from Carriers Websites - Selective Flood  [2w]
    1. [10/13/2023 - 10/17/2023 hold due to no PAD Chrome ext.] check POL in EPIC see if PL/CL AB/DB CSR
    2. [hold due to no account]download document from Selective

## Chloe:
- OPEX update
    - email sending issue
        1. [10/11/2023 - DONE] 1.0 & 2.0 result different
        2. [10/11/2023 - DONE] system call failed - added a function to re-do the email function, need a test
        3. [10/12/2023 - DONE] Out of range error
        4. [10/13/2023 - 10/23/2023 - DONE] New UAT issue
            - [10/13/2023 - DONE] Daily report new issue
            - [10/16/2023 - 10/17/2023 - DONE] Calculate error ratio issue - # error/# task
            - [10/13/2023 - DONE] An Error notification
            - [10/18/2023 - DONE] error ratio not match issue
            - [10/18/2023 - 10/19/2023 - DONE] New request submitted by Rosa: if no submitted tab in attached checklist the program will no-respond [potential solution: add a judgement before assign sheet to submitted tab]
            - [10/20/2023 - DONE] error handle added
            - [10/23/2023 - DONE] revise file name rule to validate " - ", and log tab
            - [10/24/2023 - DONE] revise audit / data tab / trainer_tab logic


- Billing Audit
    - [10/11/2023 - 10/24/2023] SIT: Test with team provided data and see if the automation result could match their manual result.
        * [10/11/2023 - 10/18/2023 - DONE] SIT with FPI/CREST/ABD/WA provided material
        * Guardian with 4 portal & Principle with 2 portal
            * [10/11/2023 - DONE] Guardian with 4 portal
            * [10/12/2023 - 10/18/2023 - DONE] principle with ENH & ENV
        * [10/23/2023 - 10/24/2023] compare when special split rule
    - [10/20/2023] UAT: Test in team with real data, team audit if the automation running properly
        * collect team feedback and maintain code per request
        * WA/ABD/CREST

    
- ABD WorkReport (Macro)[1.5w]
    - [10/13/2023 - DONE]Talk with Henry on requirements validation
    - audit report with previous month
        * [10/20/2023 - 10/23/2023]Compare Downloaded Report [https://jira.rspinternal.com/browse/PAI-8726] 




## June:
- ABD WorkReport (UiPath)[1w]
    1. login Websit(error handle for password expire notice)
        *  [10/10/2023 - DONE] error handle
        *  [10/10/2023 - DONE] revise countif method
        *  [10/11/2023 - DONE] finalize login workflow
        *  [10/11/2023 - 10/12/2023 - DONE] read group list config
        *  [10/12/2023 - DONE] read waiting period config
        *  login with MFA
    2. generate 3 kind of report and download report, Save to filetodcs
        * [10/12/2023 - 10/20/2023 - DONE] download Employee and Dependent/Beneficiary Enrollments report
        * [] download Termination report
        * [10/19/2023 - 10/24/2023] download Employee Enrollments Comparison report
        
- [10/11/2023 - DONE] DGA training macro
- [10/18/2023 - 10/20/2023 - DONE] Billing Audit MERGE DATA


### June's PENDIGN TASKS
- FPI macro YYTD REPORT [1w]
- Policy checking macro deploy in FTE team
- Admin task LKI
- Admin task - ONED run performance report and get AHT&ACC for each EE, summarize team performace
- LOCKTEN MONITOR PEAK SEASON


---
# Sprint 88&89
---
## Mason:
- [ EN & EASE done, GOCO [1/2] ] ONEDT&CREST: EN & EASE wall page extraction , GOCO portal
- [done 1/6] ENROLLMENT CHANGE part 6 carriers

## Rain:
- ABD CREAT SPD (JS)

## Chloe:
- Billing Audit
Log Difference (part2) UAT (ABD/CREST/FPI)
    1. Customization - per team

- ABD WorkReport (Macro)
audit report with previous month

## June:
- ABD WorkReport (UiPath)
    1. login Websit(error handle for password expire notice)
    2. generate report
    3. download report
    4. Save to filetodcs
