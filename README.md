A Python-based automation script that periodically scans a directory, detects and deletes duplicate files using checksum comparison, generates timestamped logs, and emails them automatically for audit purposes

Features:
  Checksum-Based Duplicate Detection — Uses hashlib (MD5) to identify exact duplicate files reliably, regardless of filename.
  Automated Log Generation — Creates timestamped log files for every execution, recording all detected and deleted duplicates.
  Scheduled Periodic Execution — Leverages the schedule library to run cleanup automatically at defined intervals without manual intervention.
  Email Reporting — Integrates smtplib to automatically send log files via email after each run for audit and monitoring purposes.

Tech Stack: Python, OS module, Hashlib, Schedule, smtplib
