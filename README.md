# Capital One Cloud Security Governance Risk Analysis 

Cloud Security Governance and Risk Analysis of the 2019 Capital One Breach. This case study evaluates cloud configuration risks, IAM control failures, and governance gaps using cybersecurity risk management principles.

## Project Overview 

This case study was conducted to:

- Analyze the root cause of the 2019 Capital One cybersecurity breach 
- Identify governance and cybersecurity risk management failures 
- Evaluate security control gaps in cloud infrastructure
- Recommend improvements to organizational security posture

## Incident Summary 

- The Capital One cybersecurity breach occurred in 2019 and affected over 100 million indivdiuals 
- The attacker exploited a misconfigured web application firewell (WAF) within the company's cloud environment
- The vulnerability allowed unauthorized access to sensitive data stores in the cloud infrastructure
- Exposed data included customer names, addresses, credit scores, credit limits, balances, and other financial information
- The incident highlighted significant weakness in cloud configuration management, identity access control, and monitoring practices

## Root Cause Analysis 

The following table identifies the primary control failures and governance weakness that contributed to the Capital One Breach 

| Security Area | Control Failure | Risk Impact | 
|---------------|-----------------|-------------|
| Cloud Configuration | Misconfigured Web application firewall allowed unauthorized access to cloud resoources | Sensitive customer data was exposed due to improper cloud configuration management | 
| Identify & Access Management (IAM) | Overly permissive IAM allowed the attacker to access sensitive storage resources | Weak access controls increased the risk of data exposure | 
| Security Monitoring | Insufficent monitoring and logging delayed detection of the atackers activity | Lack of visibility allowed the attacker to access data without immediate detection | 
| Governance & Risk Management | Inadequate cloud security governance and configuration auditing | Weak oversight increased the likelihood of configuration-related vulnerabilites | 
