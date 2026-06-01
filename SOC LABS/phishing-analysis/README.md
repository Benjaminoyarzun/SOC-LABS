# Phishing Analysis - LetsDefend

## Scenario

Investigation of a suspicious email impersonating PayPal.

## Objective

Determine whether the email represents a phishing attempt and assess potential impact.

## Evidence Sources

- Email headers
- Sender information
- Embedded URLs
- Message content

## Key Findings

- Sender domain does not match legitimate PayPal infrastructure.
- Multiple suspicious URLs identified.
- Social engineering indicators observed.
- No evidence of user interaction identified.

## Severity

Medium

## MITRE ATT&CK

- T1566.001 - Phishing: Spearphishing Attachment
or
- T1566.002 - Phishing: Spearphishing Link

(depending on the lab details)

## Repository Contents

- findings.txt
- iocs.txt
- recommendations.txt
- notes/raw_analysis.txt

## Conclusion

The email was classified as phishing. No evidence of user interaction or additional impact was identified within the available visibility.