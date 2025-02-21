# Proactive.PKI.System.Center.Central.Utilities.Certificates.Customizations 1.0.1.2

Download ([here](https://github.com/theKevinJustin/PKIAddendum/blob/main/Proactive.PKI.System.Center.Central.Utilities.Certificates.Customizations.xml))

Download Instructions ([here](https://github.com/theKevinJustin/PKIAddendum/blob/main/21%20Feb%202025%20-%20Updating%20PKI%20addendum.pdf))

Proactive.PKI.System.Center.Central.Utilities.Certificates.Customizations - 
Management pack provides multiple capabilities, including: Custom groups for multiple roles and applications, overrides which allow differentiation for all groups, organizational differences for internal and external certificate expiration alerts, validity, and self-signed certificates for multiple applications.

Pack functionality includes:
	• Groups created to Discover and monitor certificates in server certificate stores
	• Critical alert for expired certificates
	• Warning alert for invalid certificate chains, self-signed certificates, and revoked scenarios
	• PKI certificate monitoring includes views in SCOM Console, for valid, about to expire, invalid, and more
	• Update groups that utilize existing CA Auto-enrollment templates to help administrators know when manual intervention is required that template did NOT replace certificate
	• Updates default 'about to expire' alerts to 60 day warning alerts, 30 day critical
		The groups allow breakout for DC, RDP, OCSP, Internal and external issued certificates
Allows monitoring to be adjusted per organizational standards and procedures.![image](https://github.com/user-attachments/assets/aebb3abd-822c-40ec-aed9-84435d0787b1)


# Version History:
```
v1.0.1.3   4 Jan 2024 Override GUID updates and cleanup
v1.0.1.2   6 Jul 2023 Splunk, SMSIssued, and VEEAM certificate validity monitor overrides
v1.0.1.0  24 Apr 2023 Override groups for invalid certificate alerts, additional certificate store workflows for Remote Desktop registry store
v1.0.0.8  13 Apr 2023 Updated with Remote Desktop store DS/PA/Discovery per Cyber team request
v1.0.0.5  24 Feb 2023 Updated with Self-signed certs for SCCM/MECM, SolarWinds, Splunk, and VEEAM
v1.0.0.4  25 Jan 2023 Updated to human readable content, created Issuer/regex groups for different cert alert actions
v1.0.0.1  19 Sep 2022 Updated for Computer cert template group
v1.0.0.0   3 Aug 2020 Created PKI certificate customizations pack
