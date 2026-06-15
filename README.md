# Cybersecurity Technology Renewal Financial Tracking Dashboard


This project simulates the responsibilities of a Cybersecurity Financial Operations Specialist by tracking enterprise cybersecurity technology renewals, annual software spend, vendor lifecycle management, purchase order (PO) status, business criticality, and renewal risk.

The project was developed in Microsoft Excel to model how organizations manage cybersecurity technology portfolios to prevent operational disruption caused by missed renewals while improving financial visibility and forecasting. In this example, the company is a huge retailer with thousands of stores across the US.

A dashboard tab was created to provide leadership-level visibility into cybersecurity technology risk, procurement status, and projected spend through KPI metrics and visual reporting.

Red = less than 30 days, yellow = 30-60 days, green = 90 days or greater
<img width="1077" height="233" alt="Screenshot 2026-06-14 at 4 53 31 PM" src="https://github.com/user-attachments/assets/59b6220e-7289-4b6f-8daf-b7d5e0204567" />
<img width="1354" height="330" alt="Screenshot 2026-06-14 at 6 44 02 PM" src="https://github.com/user-attachments/assets/e340ee47-e768-4cc9-a195-68b4c8da507a" />

There are 3 different products with renewal dates coming up inside of 30 days. Priority is based on business criticality, operational impact, & time to recover.

The first priority amongst those red items would be Palo Alto NGFW. For a large retailer with thousands of stores, I’d prioritize Palo Alto NGFW first because it protects core network infrastructure supporting store connectivity, payment systems, VPN access, and internet-facing services. A lapse in firewall protection could increase enterprise-wide risk and potentially impact business operations at scale, so I would prioritize it to reduce operational disruption.

The second priority amongst those red items would be CyberArk. With this example being a huge retailer with thousands of stores, there are thousands of priveleged accounts, POS sytem administrators, server admins, domain admins, & cloud admins. If CyberArk expires, administrative access to critical systems could be disrupted which in turn affects stores, identity systems, infrastructure, & emergency response. Retail stores are also major ransomeware targets, so PAM (Priviledged Access Management) is huge.

The third priority would be Recorded Future threat intelligence. If this were to expire today nothing breaks or gets exposed immediately. Outside of security visibilty becoming slightly less effective, the business still functions.
