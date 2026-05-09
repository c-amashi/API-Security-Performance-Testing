# API Security & Performance Testing Project

## Overview
This project focuses on performing security and performance testing on APIs. The goal was to identify vulnerabilities and evaluate system behavior under different load conditions.

---

## Tools Used
- Postman – API Testing
- Apache JMeter – Performance Testing
- Jira – Bug Tracking

---

## Security Testing
Security testing was performed to identify:
- Unauthorized access issues
- Data exposure vulnerabilities
- Input validation problems

### Key Findings:
- API allows access without authentication
- Sensitive data is exposed in responses
- Lack of proper input validation

---

## Performance Testing
Performance testing was conducted using JMeter with multiple users.

### Test Configuration:
- Users: 10, 50, 100
- Ramp-up: 5–20 seconds

### Results Summary:

| Users | Avg Response Time | Error % | Throughput |
|------|------------------|--------|------------|
| 10   | 781 ms           | 0%     | 2.1/sec    |
| 50   | 620 ms           | 0%     | 4.9/sec    |
| 100  | 645 ms           | 0%     | 26.9/sec   |

---

## Bug Tracking (Jira)
Defects were tracked using Jira.

### Identified Bugs:
- Unauthorized Access (High)
- Data Exposure (High)

---
## Report

## Screenshots

## Author
W.A.D. Chaduki Amashi
