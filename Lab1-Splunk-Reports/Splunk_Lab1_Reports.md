# Splunk Lab 1 — Reports & Base Searches

## Goals
- Run a base search in Splunk.  
- Save searches as reports for re-use.  
- View and verify saved reports.  

---

## What I Did
- Executed a base search on sample log data.  
- Used the “Save As” menu to save the search as a report.  
- Added a title and description in the report dialog.  
- Verified the report appeared in the Reports listing.  
- Opened and viewed the saved report page.  

---

## Commands Used
```spl
index=security sourcetype=linux_secure "failed password"
