# Excel-Security-log-Analysis

This project demonstrates analyzing authentication log data using Excel to identify suspicious login behavior and repeated failed authentication attempts.

---

### Dataset
- Simulated authentication logs stored in CSV format
- Fields include timestamp, user ID, username, source IP, application, action, status, and details

---

### Analysis Performed
- Used COUNTIFS to calculate the total number of failed login attempts per user across all log events
- Applied conditional formatting to visually flag users exceeding a failed login threshold
- Built pivot tables to summarize authentication failures by user and source IP

---

### Key Findings
- Identified users with repeated failed login attempts consistent with brute-force behavior
- Observed MFA related failures and account lockout events
- Distinguished isolated login failures from recurring suspicious patterns

---

### Artifacts
- `data/auth_logs.csv` — raw authentication log data
- `analysis/log_analysis.xlsx` — Excel analysis with formulas and pivot tables
- `screenshots/` — visual highlights of findings and analysis results

---

### Skills Demonstrated
- Excel formulas (COUNTIF, COUNTIFS)
- Pivot tables and filtering
- Log analysis and pattern detection
- Translating raw event data into security-relevant insights
