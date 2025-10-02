# Splunk Lab 2 — Splunk Alerts & Reports

## Goals
- Create and manage alerts.  
- Save searches and alert results as reports. 
- Schedule a report to run daily at a set time.
- Practice SOC-relevant Splunk functions.  

---

## What I Did
- Created a new alert based on failed login attempts. 
- Viewed and verified the alert in the Alerts dashboard.  
- Disabled the alert after testing.  
- Saved a search as a report.  

---

 ## Evidence  

### Step 1 — Created new alert (Failed Logins)  
![Create Alert](01_create_an_alert.png)  

### Step 2 — Viewed the alert in Alerts dashboard  
![Alerts Dashboard](02_view_the_alert.png)  

### Step 3 — Disabled alert after testing  
![Disabled Alert](03_disable_the_alert.png)  

### Step 4 — Saved search as a report  
![Saved Search Report](04_save_search_as_report.png)  

### Step 5 — Saved alert results as report  
![Saved Alert Results](05_save_alert_results_as_report.png)  

### Step 6 — Scheduled report at 6:00 a.m.  
![Scheduled Report](06_schedule_failed_logins_report_at_6am.png)  


---

## Commands Used
index=security sourcetype=linux_secure "failed password"

---

## Skills Demonstrated

Splunk alert creation & management

Report building & scheduling

Automated monitoring workflows

Search query refinement

SOC-ready alerting/reporting practices

Saved the alert results as a separate report.

Scheduled the Failed Logins Report to run daily at 6:00 a.m.













