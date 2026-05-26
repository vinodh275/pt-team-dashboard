# pt-team-dashboard
PT Team CFM Diagnostic Dashboard — Live performance analytics, root cause diagnosis &amp; action planning for Personal Training centers across India
# PT Team — CFM Diagnostic Dashboard

A mobile-first web app for Personal Training CFMs (Center Floor Managers) 
to monitor, diagnose, and act on center performance in real time.

## What it does
- Shows all centers under each CFM ranked by risk level (At Risk / Watch / On Track)
- Diagnoses WHY a center is underperforming — AOV drop, trial decline, pack mix shift, renewal issues, trainer activation
- Gives a specific Action Plan for each underperforming center
- Tracks Pack Split % trend (Jan → now) and New/Repeat AOV trend month-over-month
- Rankings screen to compare centers across any metric

## Data sources
- Center-level performance sheet (MTD, LMTD, trials, AOV, trainers, renewals)
- L2 metrics sheet (city-wise & center-wise pack split, New AOV, Repeat AOV — Jan to now)

## Tech
Single HTML file — no install, no login, no framework.
Opens on any phone or laptop browser instantly.
Data fetched live from Google Sheets via Apps Script proxy.

## Access
Internal tool — for PT Team CFMs only.
