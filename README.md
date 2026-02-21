# FUTURE_CS_03
API Security Risk Analysis – Task 3

Cyber Security Internship – Future Interns

Overview

This repository contains the submission for Task 3 of the Cyber Security Internship program at Future Interns.

The objective of this task was to perform a structured API Security Risk Analysis on a public demo API. The assessment was conducted in a read-only manner without exploitation, focusing on identifying potential risks, security misconfigurations, and infrastructure exposure.

Objective

Analyze public API endpoints

Inspect authentication requirements

Review response headers

Identify potential security risks

Classify risk severity

Suggest remediation steps

Tools Used

Postman

Kali Linux

Public Test API (ReqRes)

Scope
In Scope

Public demo API endpoints

GET requests

Header inspection

Authentication observation

Rate limiting review

Out of Scope

Exploitation attempts

DoS testing

Authentication bypass

Testing private systems

Methodology

Reviewed API documentation

Performed endpoint testing using Postman

Analyzed response headers

Observed authentication behavior

Classified risks based on impact

Key Findings
1. Unauthenticated Endpoint Access

Public endpoints responded without authentication.
Risk Level: Medium

2. Infrastructure Information Disclosure

Response headers exposed server and framework-related information.
Risk Level: Low

3. CORS Header Observation

Access-Control headers were present and reviewed for configuration analysis.
Risk Level: Low

4. Rate Limiting Indicators

Rate limit headers were observed in responses.
Risk Level: Informational

Business Impact

If similar configurations exist in production systems, risks may include:

Data scraping

Exposure of sensitive information

Infrastructure fingerprinting

Increased attack surface

Remediation Recommendations

Implement strong authentication (JWT / OAuth2)

Apply Role-Based Access Control (RBAC)

Remove unnecessary response headers

Enforce strict CORS policies

Apply rate limiting and monitoring

Follow OWASP API Security Top 10

Repository Contents

Detailed Security Report (PDF)

Postman Testing Screenshots

Documentation of methodology and findings

Learning Outcome

This task enhanced practical understanding of:

API inspection

Response validation

Security risk identification

Structured vulnerability reporting
