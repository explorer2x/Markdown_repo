# Sprint 101

---

## Mason:

- EBCOE BCBSIL design enroll entry
  - [03/11/2024 - 03/13/2024 - DONE] handle locate company result(multiple/single/NF)
  - [03/13/2024 - DONE] Locate EE and handle locate result(multiple/single/NF)
  - [03/14/2024 - 03/18/2024 - DONE] draft workflow map for current PAD workflow - LOGIN BCBSIL, NAVIGATE to company and check EE status
  - [03/15/2024 - DONE] SIT LOGIN BCBSIL, NAVIGATE to company and check EE status
  - [03/14/2024 - 03/20/2024] define Data Table for EN and BCBSIL
  - [03/19/2024 - 03/20/2024] macro to fill in the Data Table
  - [03/14/2024 - 03/19/2024 - DONE] define JSON Structure for EN and BCBSIL Data Table 
  - [] macro to convert data table to JSON
  - [] JS to entry BCBSIL
  - [] PAD to invoke JS to entry in BCBSIL

- Maintain JS

  - [10/31/2023 - 11/15/2023] Delta Allied re-design due to website upgrade
  - [] MOO - occupation



## Rain:

- [02/29/2024, 03/06/2024 - 03/08/2024] HWS DB statement entry, seek if pdf could transfer to excel format and import into EPIC
- [03/08/2024 - 03/11/2024, 03/20/2024] WEB EPIC research
- [] HWS research policy checking JS solution
- [03/14/2024 - DONE] M3 generate proposal flat renew maintain
- [03/14/2024 - DONE] observed AAD claim VC program
- [03/15/2024 - DONE] AAD claim VC program
- [03/19/2024 - DONE] AAD claim VC program decision part
- [03/15/2024 - 03/18/2024 - DONE] AAD DAS report macro
- [03/19/2024 - DONE] AAD claim setup maintain changes

### Rain pending

- [] a universal tool to modify asset in Orch
- [] HWS EPIC redesign
- [] M3 EPIC redesign



## Chloe:

- OPEX issue
  - [02/27/2024 - 03/19/2024] peer review audit issue, audit tracklog and log error
  - [03/19/2024 - ?] SIT
- [03/18/2024 - 03/22/2024] ADP Work Report Compare macro debug
  - [] SIT Employee and Dependent/Beneficiary Enrollments report
  - [] SIT Termination report
  - [] SIT Employee Enrollments Comparison report
  - [] update CONFIG file following reusable rule
- [03/12/2024 - 03/18/2024 - DONE] THH Cumberland bug fix

### Chloe Pending

- ABD Work Report Compare
  - [] set up config for # system # report type
  - [] update macro to compare 2 reports per config
  - [] SIT 1 system report with all report type
  - [] UAT

- ABD Work Report Downloaded Report - ? system
  1. login Website (error handle for password expire notice)
  2. generate 3 kind of report and download report, Save to filetodcs
  3. SIT the bot






- Billing Audit
  - [02/28/2024 - DONE] run macro with test file to generate new result files, check if same with previous file
  - [03/04/2024 - DONE] send file to Henry
  - [] CBIZEB UAT
  - [] FIA UAT
  - [] BLT?


# Sprint 100

---

# Mason:

- EBCOE project
  [02/28/2024 - DONE] test and deploy pull js code from SharePoint
  [02/28/2024 - DONE] share finding in log msg 


## Mason Pending

- BCBSIL design enroll entry
  - [02/29/2024 - 03/01/2024 - DONE] define login method
  - [03/04/2024 - 03/06/2024 - DONE] develop login workflow and SIT
  - [03/06/2024 - DONE] code review with Betty
  - [03/06/2024 - DONE] review with Betty on OPEX Template Work Log and DC Template
  - [03/07/2024 - 03/08/2024 - DONE] pull phone with GET and benefit summary(plan info)
  - [03/11/2024] handle locate company result(multiple/signle/NF)

- [02/29/2024 - DONE] print pdf for all give urls and send to SDU for audit
- [03/07/2024 - DONE] transfer OPEX updated code and workflow map to Chloe



## Mason Pending

- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template

- [11/14/2023 - 11/17/2023, 12/06/2023, 12/19/2023] GDP Shortclaim develop


# Rain:

- [02/29/2024, 03/06/2024 - 03/08/2024] HWS DB statement entry, seek if pdf could transfer to excel format and import into EPIC
- [03/08/2024 - 03/11/2024] WEB EPIC
- [] HWS research policy checking JS solution
- [02/29/2024 - 03/06/2024 - DONE] M3 close ZENDESK, PROD ENV issue
- [03/01/2024 - DONE] AAD claim issue

## Rain pending

- [] AAD claim VC program, low volume, postpone
- [] AAD tracking log format 
- [] a universal tool to modify asset in Orch


# Chloe:

- OPEX issue
  [02/27/2024 - 03/08/2024 - DONE] peer review audit issue
  [03/07/2024 - 03/08/2024 - DONE] exclude file name
  [03/04/2024 - 03/05/2024 - DONE] fix enmergency issue from Rosa: AQL not correct, root casue is error ratio report not match daily report
  [03/05/2024 - 03/07/2024 - DONE] folder issue, when run email only, change to p drive


- ABD Work Report Compare Downloaded Report
  [] macro error when running in SDU 
  [] debug and update to UIPATH


- Billing Audit
  [02/28/2024 - DONE] run macro with test file to generate new result files, check if same with previous file
  [03/04/2024 - DONE] send file to Henry
  [] CBIZEB UAT
  [] FIA UAT
  [] BLT?

- [02/28/2024 - DONE] merchants login issue maintain

# Sprint 98 - 99

---

## Mason:

- [12/12/2023 - 12/15/2023, 02/05/2024 - DONE] document BRD with Rosa's requirement

- OPEX audit function redesign
  [01/09/2024 - 01/30/2024]

- EBCOE project
  [02/05/2024 - DONE] prepare demo with OPEX to show the automation capibility
  [02/05/2024 - DONE] update workflow to hanlde multiple company
  [02/06/2024 - DONE] demo with OPEX to show the automation capibility
  [02/19/2024 - DONE] test function to pull wall notification per date
  [02/20/2024 - DONE] test function on betty's server to loop and get wall per date, then handle EE info extraction
  [02/22/2024 - DONE] handle EE info extraction
  [02/23/2024 - DONE] test PAD whole solution on betty's server
  [02/23/2024 - DONE] observation on Enrollment & Eligibility Process for Chicago Office in CBIZB carrier BCBS IL

- [02/01/2024 - DONE] GDP macro to download report, maintain code to involve more report type

- web printting
  [02/16/2024 - DONE] web printting, python to generate url list and print each url to pdf, combine sub-url pdfs per tabs
  [02/16/2024 - DONE] demo with SDU
  [02/26/2024] update code per SDU feedback and get back to Mandy

# Mason Pending

- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template
- Maintain JS
  * [10/31/2023 - 11/15/2023] DeltaAllied re-design due to website upgrade
  * [] MOO - occupation

- [11/14/2023 - 11/17/2023, 12/06/2023, 12/19/2023] GDP Shortclaim develop


# Rain:

- [12/14/2023 - 12/20/2023, 01/08/2024 - 01/19/2024, 01/25/2024 - 01/26/2024, 01/31/2024 - 02/06/2024 - DONE] M3 Generate proposal flat renew
  [02/22/2024 - 02/23/2024 - DONE] fix UAT issue: dup string in PDF extraction

- [] HWS DB statement entry, seek if pdf could transfer to excel format and import into EPIC
- [02/26/2024 - DONE] M3 Generate proposal attach file


- [01/29/2024 - DONE] HWS Policy Checking
- [02/02/2024 - DONE] M3 close ZENDESK maintain
- [02/05/2024 - DONE] HWS Policy Checking macro error fix
- [02/05/2024 - DONE] AAD India bot run server error
- [02/16/2024 - 02/17/2024] THH condo order lossrun special case and test


## Rain pending

- [] AAD claim VC program, low volume, postpone
- [] a universal tool to modify asset in Orch
- [] HWS DB STATEMENT USE PDF2EXCEL LIB TO CONVERT NEW DB TEMPLATE/DEV PDF2EPIC WITH VBA
- [] HWS re-write EPIC web automation - DB statement entry

# Chloe:

- OPEX issue
  * [01/30/2024 - DONE] # of task on EB tasks
  * [01/30/2024 - 01/31/2024 - DONE] split ", or" in answer
  * [01/31/2024 - 02/02/2024 - DONE] highlight error in EE checklist
  * [02/14/2024 - 02/20/2024 - DONE] audit racking log & peer review
  * [02/26/2024] design trainer tab's chart
  * [] exclude file name

- ABD WorkReport Compare Downloaded Report
  * [] macro error when running in SDU UAT
  * [] debug and update to UIPATH

- Billing Audit (new carrier deploy: Kaiser & Cigna & HealthPartner)
  * [01/11/2024] code review on Merge data section
  * [01/25/2024, 02/05/2024] UAT with Henry's requirement on Merge data

- [02/05/2024 - DONE] DDD maintain


# Sprint 97

---

## Mason:

- [12/12/2023 - 12/15/2023] document BRD with Rosa's requirement

- OPEX audit function redesign
  [01/09/2024 - 01/30/2024]

- EBCOE project
  * [01/18/2024 - DONE] review project Tech enable workflow Master sheet
  * [01/22/2024 - 01/25/2024 - DONE] assess the tech solution on JS and PAD to extract EE wall page
  * [01/25/2024 - DONE] dev JS code to extract wall info into JSON string and insert in webpage with new element
  * [01/25/2024 - DONE] dev PAD worflow to convert JSON to csv file and save to given folder
  * [01/26/2024 - DONE] dev PAD PS code to convert JSON to csv file and save to given folder
  * [01/26/2024 - DONE] dev PAD worflow to extract JS code from outside source and insert into PAD variable


- GA website printing
  * [01/19/2024 - DONE] python function assessment on getting urls and print to PDF

- [01/16/2024 - DONE] GDP update ddd code to run every month on 2nd & 16th 

# Mason Pending

- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template
- Maintain JS
  * [10/31/2023 - 11/15/2023] DeltaAllied re-design due to website upgrade
  * [] MOO - occupation
  * [12/4/2023 - DONE] Allsaver

- [11/14/2023 - 11/17/2023, 12/06/2023, 12/19/2023] GDP Shortclaim develop


# Rain:

- [12/14/2023 - 12/20/2023, 01/08/2024 - 01/19/2024, 01/25/2024 - 01/26/2024] M3 Generate proposal flat renew
- [01/16/2024 - DONE] AAD task observation: AAD online Daily report & AAD DAS new request
- [01/17/2024 - DONE] HWS task assignment 
- [01/22/2024 - DONE] HWS policy checking task maintain
- [01/22/2024 - 01/23/2024 - DONE] AAD online Daily report
- [01/18/2024 - DONE] AAD DAS new request: pull  number and format data from online form, sync to online form in afternoon
- [01/24/2024 - DONE] AAD DAS new request:pull previuos day data from online form
- [01/23/2024 - DONE] HWS task observation Update EPIC per policy
- [01/29/2024] HWS Policy Checking

### Rain pending

- [] AAD claim VC program, low volume, postpone
- [] a universal tool to modify asset in Orch
- [] HWS DB STATEMENT USE PDF2EXCEL LIB TO CONVERT NEW DB TEMPLATE/DEV PDF2EPIC WITH VBA  
- [] HWS re-write EPIC web automation - DB statement entry



## Chloe:

- OPEX issue
  * [01/05/2024 - DONE] design TLreport function workflow
  * [01/09/2024 - 01/18/2024 - DONE] re-write TLreport function and SIT
  * [01/17/2024 - 01/18/2024 - DONE] design Trainee report function workflow
  * [01/19/2024 - DONE] re-write Trainee report function and SIT
  * [01/22/2024 - DONE] add move file from c to p drive
  * [01/22/2024 - 01/25/2024 - DONE] fix bugs Rosa notified
  * [01/26/2024 - 01/29/2024 - DONE] add new functions per Rosa's needs: add Trainer Tab chart
  * [01/30/2024] # of task on EB tasks

- ABD WorkReport Compare Downloaded Report
  * [] macro error when running in SDU UAT
  * [] debug and update to UIPATH

- Billing Audit (new carrier deploy: Kaiser & Cigna & HealthPartner)
  * [01/11/2024] code review on Merge data section
  * [01/25/2024] UAT with Henry's requirement on Merge data


## June:

- [01/10/2024 - 01/12/2024] DDD maintain ENCOMPASS in DDIB
  * [01/11/2024] SIT 

- Billing Audit 
  * [] new carrier (BCBS UHC)
  * [01/12/2024] update code per feed back, need SIT

- ABD WorkReport (UiPath)
  * [] remove dup
  * [] filetodecs by group
  * [] upload to Azure blob
  * [01/05/2024 - 01/12/2024] missing document due to error, wrongly pick date
  * [] handle email verification auto-fwd in SDU outlook



# Sprint 96

---

## Mason:

- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template
- Maintain JS
  * [10/31/2023 - 11/15/2023] DeltaAllied re-design due to website upgrade
  * [] MOO - occupation
  * [12/4/2023 - DONE] Allsaver

- [01/04/2023 - 01/08/2023 - DONE] GDP JS - Hartford, UHC cobra, TASC
- [11/14/2023 - 11/17/2023, 12/06/2023, 12/19/2023] GDP Shortclaim develop
- [12/12/2023 - 12/15/2023] document BRD with Rosa's requirement
- [01/04/2023 - DONE] performance review form

- OPEX Tina's issue
  * [12/26/2023 - DONE] debug the Macro logic
  * [01/04/2023 - DONE] meeting with Rosa Melody and Tina to explain the debugging method
  * [01/04/2023 - 01/05/2023 - DONE] try to modify the Macro to use a local folder as a temporary transfer station instead of opening/saving file in P drive directly
  * [01/08/2023 - DONE] UAT with Rosa on audit function

- OPEX audit function redesign
  [01/09/2024 - 01/15/2024]

- [01/16/2024] GDP update ddd code to run every month on 2nd & 16th 


## Rain:

- [12/14/2023 - 12/20/2023, 01/08/2024 - 01/16/2024] M3 Generate proposal flat renew
- [01/03/2024 - 01/04/2024 - DONE] New AAD report format
- [01/05/2024 - DONE] performance review form

### Rain pending

- [] AAD claim VC program, low volume, postpone
- [] a universal tool to modify asset in Orch
- [] HWS DB STATEMENT USE PDF2EXCEL LIB TO CONVERT NEW DB TEMPLATE/DEV PDF2EPIC WITH VBA  
- [] HWS re-write EPIC web automation - DB statement entry
- [] AAD online Daily report


## Chloe:

- OPEX issue
  * [01/04/2024] SDD audit tool
  * [01/09/2024 - 01/10/2024] re-write TLreport function
  * [01/05/2024] design TLreport function workflow
  * [] add new functions per Rosa's needs

- ABD WorkReport Compare Downloaded Report
  * [] handle UAT issue

- Billing Audit (new carrier deploy: Kaiser & Cigna & HealthPartner )
  * [01/11/2024] code review on Merge data section
  * [] UAT with Henry's requirement on Merge data

- [01/04/2024 - 01/08/2024 - DONE] Merchants DDD maintain
- [01/05/2024 - 01/08/2024 - DONE] performance review form

## June:

- [01/04/2024 - DONE] DDD maintain Liberty
- [01/10/2024 - 01/12/2024] DDD maintain ENCOMPASS in DDIB
  * [01/11/2024] SIT 
- [01/04/2024, 01/05/2024 - DONE] locktonEB new requirement, add function according to team's new requirement, release to team
- [] remove automation file due to RIA Cancel 

- Billing Audit 
  * [01/11/2024] new carrier (BCBS UHC)
  * [01/09/2024 - DONE] issue fix: plan name matching, update config
  * [01/09/2024 - DONE] issue fix: blank column filling error
  * [01/12/2024] update code per feed back

- ABD WorkReport (UiPath)
  * [] remove dup
  * [] filetodecs by group
  * [] upload to Azure blob
  * [01/05/2024 - 01/12/2024] missing document due to error, wrongly pick date

- [] confirm saving with team 


# Sprint 95

---

## Mason:

- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template
- Maintain JS
  * [10/31/2023 - 11/15/2023] DeltaAllied re-design due to website upgrade
  * [] MOO - occupation
  * [12/4/2023] Allsaver UAT

- [11/14/2023 - 11/17/2023, 12/06/2023, 12/19/2023] GDP Shortclaim develop

- [12/12/2023 - 12/15/2023] document BRD with Rosa's requirement
- [12/19/2023 - DONE] meeting with Angel and Chloe on OPEX coding update priority
- [12/20/2023 - DONE] meeting with Norman on EBCOE workflow and demo EN WALL js solution
- [11/22/2023, 12/21/2023 - DONE] CREST EN WALL ACTIVITY JS & audit macro
- [12/26/2023 - DONE] test and coding for EN API
- [12/27/2023 - DONE] call for meeting with ISAAC
- [1/2/2024 - DONE] GDP birthday report macro

- OPEX Tina's issue
  * [12/26/2023 - DONE] debug the Macro logic.
  * [12/28/2023] book meeting with Rosa Melody and Tina to explain the debugging method
  * [12/26/2023] try to modify the Macro to use a local folder as a temporary transfer station instead of opening/saving file in P drive directly



## Rain:

- [11/29/2023 - 12/05/2023，12/20/2023 - DONE] M3 downloading maintain
- [12/14/2023 - 12/20/2023] M3 Generate proposal flat renew
- [12/20/2023 - DONE] review Lib and update WIKI
- [12/20/2023 - DONE] solution team work SDD update and QA
- [12/25/2023 - DONE] AAD 2 macro AND policy & claim set up manage workflow
- [12/26/2023 - 12/28/2023 - DONE] AAD report format

### Rain pending

- [] AAD claim VC program, low volume, postpone
- [] a universal tool to modify asset in Orch
- [] HWS DB STATEMENT USE PDF2EXCEL LIB TO CONVERT NEW DB TEMPLATE/DEV PDF2EPIC WITH VBA  



## Chloe:

- ABD WorkReport Compare Downloaded Report
  * [12/27/2023 - 12/28/2023] UAT with team
  * [12/25/2023 - DONE] bug fix: the previous macro on column name/index

- ABD saving issue
  * [12/21/2023 - DONE] talk to team to validate saving #

- Billing Audit (new carrier deploy: Kaiser & Cigna & HealthPartner )
  * [12/20/2023 - DONE] HealthPartner SIT
  * [12/25/2023 - DONE] bug fix: remove dup answer & dup answer report discrepancy when log answer
  * [12/26/2023 - DONE] Vlife validate error, update config and code


- OPEX project
  * [12/20/2023 - DONE] audit result error
  * [12/05/2023-12/13/2023, 12/20/2023 - DONE] test if running in local can fix issue - modified the code to running and storing the files locally on the desktop, run the local version when the current P drive version encounter any email sending failure.
  * [12/20/2023 - DONE] test if increase RAM could fix the issue - test on a high-performance device on our side, added code to switch the Outlook account between the NHBC account and our personal Outlook account, depending on the environment. conduct a test with the same auditing materials on our device as soon as Rosa reports any email issues.
  * [12/20/2023 - DONE] change code to handle renaming error when have extra space in file name


## June:

- ABD WorkReport (UiPath)
  * [] remove dup
  * [] filetodecs by group
  * [] upload to Azure blob
  * [12/19/2023 - DONE] remove button when download
  * [12/19/2023 - DONE] get date text to validate if date input succeed
  * [12/21/2023 - 12/26/2023 - DONE] image click failed, change selector to URL, refine structure
  * [12/27/2023 - DONE] date picker cannot fill issue, change entry method to picker calendar

- Billing Audit
  * [12/25/2023 - DONE] HealthPartner SIT 
  * [12/25/2023 - DONE] SSN type dismatch error

- [12/14/2023 - 01/02/2024 - DONE] DDD maintain liberty 
- [] DDD maintain DDIB
- [12/20/2023 - DONE] ONED performance report update
- [01/03/2024] locktonEB new requirement
- [12/28/2023 - 01/02/2024- DONE] ASA new requirement on template


# Sprint 94

---

## Mason:

- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template
- Maintain JS
  * [10/31/2023 - 11/15/2023] DeltaAllied re-design due to website upgrade
  * [] MOO - occupation
  * [11/17/2023 - 12/1/2023 - DONE] Allsaver re-write
  * [12/4/2023] Allsaver UAT

- [11/22/2023] CREST ENWALL ACTIVITY JS & audit macro

- [12/07/2023 - DONE] meeting with OPEX to validate the detailed needs.
- [12/07/2023 - DONE] meeting with Norman on EBCOE workflow
- [12/08/2023 - 12/11/2023 - DONE] meeting with Isaac on EBCOE workflow issues
- [11/14/2023 - 11/17/2023, 12/06/2023] GDP Shortclaim develop

- [12/12/2023 - 12/15/2023] document BRD with Rosa's requirement
- [12/15/2023 - DONE] task observation on GDP Catherine's requirement
- [12/14/2023 - DONE] meeting with Norman on EBCOE workflow
- [12/18/2023 - DONE] update GDP code
- [12/18/2023 - 12/19/2023 - DONE] update python code to generate report chart

## Rain:

- [12/06/2023 - 12/14/2023 - DONE] AAD maintain daily report
- [11/29/2023 - 12/05/2023，12/19/2023] M3 downloading maintain
- [12/14/2023 - 12/18/2023] M3 Generate proposal flat renew


### Rain pending

- [] HWS re-write EPIC web automation - DB statement entry
- [] AAD claim VC program
- [] AAD prepare a document for error collection, before Dec.
- [] a universal tool to modify asset in Orch
- [] HWS DB STATEMENT USE PDF2EXCEL LIB TO CONVERT NEW DB TEMPLATE/DEV PDF2EPIC WITH VBA


## Chloe:

- ABD WorkReport Compare Downloaded Report
  * [11/27/2023 - DONE] SIT pending issue: compare & log
  * [] download last term doc & upload
  * [] UAT
  * [12/06/2023 - DONE] code review on audit

- Billing Audit (new carrier deploy: Kaiser & Cigna (BCBS & UHC) - Cigna)
  * [12/01/2023] SIT
  * [12/06/2023] modify code for 4 new carrier
  * [12/06/2023 - 12/08/2023] modify code for "-"
  * [12/11/2023 - 12/15/2023] only plan name and info - add info into Medical & Dental plan for Carrier  & Ease (Address 3 = City + State + Zip)
  * [12/11/2023 - DONE] Remove duplicate audit result and clear plan type on the kept row
  * [12/14/2023 - DONE] revise code to remove symble except 0-9a-zA-Z.

- OPEX project
  * [11/23/2023 - 11/28/2023] fix email report issue
  * [] audit result error
  * [12/13/2023] rename NH file issue found on 1207
  * [12/05/2023-12/13/2023] test if running in local can fix issue - modified the code to running and storing the files locally on the desktop, run the local version when the current P drive version encounter any email sending failure.
  * [] test if increase RAM could fix the issue - test on a high-performance device on our side, added code to switch the Outlook account between the NHBC account and our personal Outlook account, depending on the environment. conduct a test with the same auditing materials on our device as soon as Rosa reports any email issues.
  * [] revise code if no other approach could fix the issue


- ABD saving issue
  * [] talk to team to validate saving #


## June:

- ABD WorkReport (UiPath)
  * [] remove dup
  * [] filetodecs by group
  * [12/07/2023] update group list
  * [] upload to Azure blob
  * [12/14/2023] debug missing compariation report
  * [12/18/2023] remove button when download

- Billing Audit
  * [12/4/2023 - 12/08/2023 - DONE] new carrier deploy: Kaiser & Cigna & Delta Dental
  * [12/05/2023 - 12/07/2023 - DONE] update config and code for EN-V
  * [12/11/2023 - DONE] HealthPartner update config, replace relation code, update vertical template
  * [12/11/2023 - DONE] Tier - replace 1,2,3 with tier before copy data
  * [12/15/2023 - DONE] New Function: Convert Full state into abbr. before audit
  * [12/15/2023 - DONE] update config on Carrier name to add "Vertical" to use vertical copy
  * [12/15/2023 - DONE] Team special requirement: do not audit Plan name - patric dental - !!!Solution pendin


- [12/14/2023 - 12/18/2023] DDD maintain liberty & DDIB
- [] performance report update
- [12/08/2023 - DONE] locktonEB new requirement: task assignment, track forcast# & actual# (total 50min/save5~6min)
- [12/19/2023 -DONE] Crest login test


# Sprint 93

---

## Mason:

- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template
- [10/25/2023 - 10/26/2023 - DONE] debug on THH CNA "Failed to establish connection to file storage server"
- [] validate saving data with GDP team on Sept data
- Maintain JS
  * [10/31/2023 - 11/15/2023] DeltaAllied re-design due to website upgrade
  * [] MOO - occupation
  * [11/17/2023 - 12/1/2023 - DONE] Allsaver re-write
  * [12/4/2023] Allsaver UAT

- [11/14/2023 - 11/17/2023] GDP Shockclaim develop
- [11/22/2023] CREST ENWALL ACTIVITY JS & audit macro
- [11/28/2023 - DONE] catch up with SDU team on ENROLLMENT task
- [11/28/2023 - 11/29/2023 - DONE] update macro for GDP new server issues
- [11/29/2023 - DONE] meeting with Chloe Iris and Angel on OPEX 2024 project, send meeting request to OPEX.


## Rain:

- [11/23/2023 - DONE] AAD Observation
- [] AAD maintain daily report
- [11/27/2023 - DONE] M3 & HWS Observation
- [11/28/2023 - 11/30/2023 - DONE] prepare monthly meeting sharing
- [11/29/2023 - 12/5/2023] M3 downloading maintain
- [11/29/2023 - DONE] HWS maintain Macro
- [11/30/2023 - DONE] HWS maintain policy checking list Macro

### Rain pending

- HWS re-write EPIC web automation - DB statement entry
- M3 Generate proposal flat renew
- AAD claim VC program
- AAD prepare a document for error collection, before Dec.
- [] a universal tool to modify asset in Orch
- [] HWS DB STATEMENT USE PDF2EXCEL LIB TO CONVERT NEW DB TEMPLATE/DEV PDF2EPIC WITH VBA


## Chloe:

- ABD WorkReport Compare Downloaded Report
  * [11/27/2023 - DONE] SIT pending issue: compare & log
  * [] download last term doc & upload
  * [] UAT

- Billing Audit (new carrier deploy: Kaiser & Cigna (BCBS & UHC) - Cigna)
  * [11/30/2023 - DONE] update macro code to fit new team and Cigna
  * [11/30/2023 - DONE] add config and macro for Kaiser
  * [12/01/2023] SIT 

- OPEX project
  * [11/23/2023 - 11/28/2023] fix email report issue

- ABD saving issue
  * [] talk to team to validate saving #

- KIA DDD
  * [11/28/2023 - DONE] fix plymouth DDD error

- [11/30/2023 - DONE] THH weekly report update

## June:

- ABD WorkReport (UiPath)
  * [11/13/2023 - 11/21/2023 - DONE] upload to dev to test, then UAT, update MFA config
  * [11/28/2023 - 11/29/2023 - DONE] ABD release meeting, fix bug
  * [11/30/2023 - 12/1/2023 - DONE] create asset in production and test new group name
  * 

- Billing Audit
  * [12/4/2023] new carrier deploy: Kaiser & Cigna (BCBS & UHC) - Kaiser


- [11/27/2023 - DONE] ONED run performance report and get AHT&ACC for each EE, summarize team performace

- [] DDD maintain liberty & DDIB
- [12/1/2023 - DONE] locktonEB new requirement: task assignment, track forcast# & actual# (total 50min/save5~6min)




# Sprint 92

---

- public pending work: 
  * ABD Census Transformation
  * ABD Create Consolidated Reports
  * ABD WorkReport new portal
  * FPI TTYD Reporting

## Mason:

- [10/12/2023 - 10/13/2023, 10/23/2023 - 10/24/2023] GDP - macro to combine 3 CFO report into template
- [10/25/2023 - 10/26/2023] debug on THH CNA "Failed to establish connection to file storage server"
- [10/30/2023 - 10/31/2023] validate saving data with GDP team on Sept data
- [11/08/2023 - DONE] demo and deploy EB tool in CBIZEB team 
- Maintain JS
  * [10/30/2023 - 10/31/2023 - DONE] principle ADDRESS REMOVE #
  * [] Guardian DOH SELECT & PHONE
  * [10/31/2023 - 11/15/2023] DeltaAllied re-design due to website upgrade
  * [] MOO - occupation
  * [11/17/2023 - 11/21/2023] Allsaver re-write

- [11/13/2023 - DONE] Wex - new carrier
- [11/14/2023 - DONE] GDP Teladoc Maintain
- [11/14/2023 - 11/17/2023] GDP Shockclaim develop
- [] CREST ENWALL ACTIVITY JS & audit macro

- [] talk with Katrina on ONEDT volume using MIR actuall data


## Rain:

- [11/07/2023 - DONE] Observation: HWS Renew macro
- [11/08/2023 -11/14/2023- DONE] maintain: M3 close ZENDESK
- [11/08/2023 - DONE] test&maintain M3 downloading
- [11/08/2023 - DONE] Observation: M3JN EB task 
- [11/09/2023] AAD prepare document
- [11/13/2023 - DONE] AAD new request to extract table list from website
- [11/15/2023 - 11/20/2023] HWS Individual Renew macro
- [11/21/2023] AAD re-assign adjustor maintain


### Rain pending

- AAD prepare a document for error collection, before Dec.
- [] a universal tool to modify asset in Orch
- [] HWS DB STATEMENT USE PDF2EXCEL LIB TO CONVERT NEW DB TEMPLATE/DEV PDF2EPIC WITH VBA


## Chloe:

- ABD WorkReport Compare Downloaded Report
  * [11/07/2023 - 11/09/2023, 11/16/2023] SIT: minior changes to accelerate macro running speed, change key to dict..
  * [11/17/2023 - 11/20/2023] comparison per date
  * [] UAT
  * [] other Portals macro update

- Billing Audit
  * new carrier deploy: Kaiser & Cigna (BCBS & UHC)
  * [11/09/2023 - DONE] SIT:SSN issue, if start with 0, remove the 0 before compare
  * [11/10/2023 - 11/14/2023 - DONE] optimize code speed
  * [11/15/2023 - DONE] (https://rspproduct.atlassian.net/browse/PAI-9036) UAT with WA billing audit - name issue
  * [11/20/2023 - 11/21/2023] life & vlife merge data config update, life Done

- [11/16/2023 - 11/17/2023] OPEX project 2 issue maintain, email issue DONE, email wording issue
- [11/20/2023] OPEX project 1 new issue maintain
- [11/15/2023 - DONE] THH merchants maintain

- GDP upload to BP REPLACE WITH PAD
  * book observation with GDP team to observe upload process daily report
  * move WA code to PAD and test

## June:

- ABD WorkReport (UiPath)
  * [11/02/2023 - 11/09/2023 - DONE]SIT the bot - test the verification code forward function, add vba code in Chloe's outlook to forward verification code.
  * [11/06/2023 - 11/09/2023 - DONE]SIT the bot -  add Q&A in config for login
  * [11/17/2023 - 11/20/2023 - DONE] add group list in bot
  * [11/13/2023 - 11/21/2023] upload to dev to test, then UAT, update MFA config


- Billing Audit
  * [11/13/2023 - 11/14/2023 - DONE] (https://rspproduct.atlassian.net/browse/PAI-8861) To Do:  Copy column per config on plan level
  * [11/07/2023 - DONE] copy miss info
  * [11/09/2023 - DONE] remove non-used loop to speed up the code
  * [11/13/2023 - DONE] debug on Henry's bug, added back a config removed column
  * [11/15/2023 - 11/16/2023 - DONE] (https://rspproduct.atlassian.net/browse/PAP-2218) UAT with WA billing audit: fix tier issue
  * [11/17/2023 - DONE] 1117 version SIT
  * new carrier deploy: Kaiser & Cigna (BCBS & UHC)

- [11/13/2023 - DONE] communicate with SDU team on macro change

- locktonEB new requirement: task assignment, track forcast# & actual# (total 50min/save5~6min)

- ONED run performance report and get AHT&ACC for each EE, summarize team performace
- ONED run performance report and get AHT


## Billing Audit:

- change if tire not provided, ee spouse==> family
- Vlife issue: ee ok but spouse/child couldn't get
- plan issue, HR plan
- ABD FEEDBACK macro stucked with no clue, need change new 



# Sprint 91

---

## Mason:

- [10/25/2023 - DONE] ONEDT: talk with Katrina on saving calculation(baseline AHT and actual AHT)
- [10/26/2023 - DONE] ONEDT: talk with Nancy to find more opportunity
- [10/25/2023 - DONE] CREST follow up
- [10/27/2023 - DONE] ONEDT: create parent case JS 
- [11/03/2023 - DONE] ONEDT - d365 function and EN function
- [11/03/2023 - 11/06/2023 - DONE] THH EPIC MACRO
- [11/06/2023 - DONE] confirm with ABD on carrier deployment status

## Rain:

- [10/26/2023 - 10/31/2023 - DONE] HWS policy checking compare location
- [10/31/2023 - DONE] Task assignment macro
- [10/25/2023 - DONE] HWS policy checking compare VEH (TEST WITH BILLING AUDIT CODE)
- [10/27/2023 - DONE] M3 150 VEH compare
- [11/01/2023 - 11/02/2023 - DONE] M3 DOWNLOADING MACRO
- [11/03/2023 - DONE] demo to OPEX on HWS innovation idea
- [11/06/2023 - DONE] HWS DB STATEMENT MACRO UPDATE


## Chloe:

- OPEX update: log the bug ratio (# of audit / # of bug)
  * [10/24/2023 - DONE] cannot match
  * [10/26/2023 - DONE] date validation for 1 day trainee 
  * [10/26/2023 - DONE] email wording, Data tab have value but email says no data generated

- Billing Audit
  * [10/25/2023 - DONE] compare when special split rule
  * [10/25/2023 - DONE] change clearcontents to delete row
  * [10/25/2023 - DONE] [button logic on platform. remove popup window](https://jira.rspinternal.com/browse/PAI-8805)
  * [10/25/2023 - DONE] re-write merge name function
  * [10/26/2023 - DONE] highlight dup name function
  * [10/27/2023 - DONE] optimize code
  * [10/31/2023 - DONE] [pending optimize](https://rspproduct.atlassian.net/browse/PAI-8860)
  * [11/01/2023 - DONE] modify code to handle carrier is empty
  * [11/07/2023] SSN & Name may contains "-", need to remove all symbol before compare

- ABD WorkReport Compare Downloaded Report
  * [10/30/2023 - DONE] design SDD
  * [10/31/2023 - DONE] Get downloaded report folder.
  * [10/31/2023 - DONE] Loop folder from step 1 and get the file address that need to audit. Loop to open them.
  * [10/31/2023 - DONE] Gets the columns of the opened file in step 3 that need to audit.
  * [11/01/2023 - 11/03/2023 - DONE] Use the column filtered by step 3 and Convert download report to 2 arrays and compare. Pass an array to log record function to log discrepancy.use name and DOH as search key.
  * [11/01/2023 - 11/03/2023 - DONE] Log record function, input an array, and log each item in log sheet’s last row.




## June:

- ABD WorkReport (UiPath)
  1. login Websit(error handle for password expire notice)
     *  login with MFA
  2. generate 3 kind of report and download report, Save to filetodcs
     * [10/25/2023 - 10/26/2023 - DONE] download Termination report
     * [10/24/2023 - 10/25/2023 - DONE] download Employee Enrollments Comparison report
     * [10/24/2023 - DONE] navigate issue: cannot navigate after click button
     * [10/31/2023 - 11/01/2023 - DONE] fix Re-direct issue found in SIT when process next account(didn't clear searchbox)
     * [10/31/2023 - 11/01/2023 - DONE] add login credential to an array for looping.
  3. SIT the bot
     * [11/02/2023 - 11/07/2023] test the verification code forward function
     * [11/06/2023 - 11/07/2023] add Q&A in config for login
     * [11/06/2023 - 11/07/2023 - DONE] combine 2 logins for ALL & NEWFRONT


- [11/03/2023 - DONE] observed locktonFTE new requirement: admin task in peak season

- [11/03/2023 - DONE] observed locktonEB new requirement: task assignment,  track forcast# & actual#

- Billing Audit

  - [10/26/2023 - DONE] mark the discrepancy's orignal source

  * [pending optimize](https://rspproduct.atlassian.net/browse/PAI-8861) To Do:  Copy column per config on plan level
  * [11/07/2023] copy miss info


 - FPI	TTYD Reporting
 - Admin task - ONED run performance report and get AHT&ACC for each EE, summarize team performace


## Billing audit

 - WA PENDIGN FOR UAT
 - BKSEB PENDIGN FOR UAT


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
  1. [10/11/2023 - DONE] 1.0 & 2.0 result different
  2. [10/11/2023 - DONE] system call failed - added a function to re-do the email function, need a test
  3. [10/12/2023 - DONE] Out of range error
  4. [10/13/2023 - 10/23/2023 - DONE] New UAT issue
     * [10/13/2023 - DONE] Daily report new issue
     * [10/16/2023 - 10/17/2023 - DONE] Calculate error ratio issue - # error/# task
     * [10/13/2023 - DONE] An Error notification
     * [10/18/2023 - DONE] error ratio not match issue
     * [10/18/2023 - 10/19/2023 - DONE] New request submitted by Rosa: if no submitted tab in attached checklist the program will no-respond [potential solution: add a judgement before assign sheet to submitted tab]
     * [10/20/2023 - DONE] error handle added
     * [10/23/2023 - DONE] revise file name rule to validate " - ", and log tab
     * [10/24/2023 - DONE] revise audit / data tab / trainer_tab logic


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