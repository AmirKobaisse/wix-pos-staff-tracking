# Wix POS Staff Tracking Implementation

## Overview
A barbershop needed a way to track daily sales per employee to calculate commissions. However, their POS system was recording all transactions under a single account, making it impossible to attribute revenue to individual staff members.

## Problem
The system was not properly configured for multi-user usage. Staff accounts existed but were not fully set up or authenticated on the POS device. As a result, all transactions were assigned to one account, requiring manual tracking of commissions.

## Solution
I configured role-based access for each employee and ensured all accounts were properly activated. I then set up individual logins on the POS system and implemented PIN-based authentication to allow quick user switching during daily operations.

## Key Actions
- Investigated POS configuration and identified root cause  
- Configured staff roles and permissions  
- Set up individual user logins and PIN authentication  
- Tested transactions under multiple users  
- Created a simplified workflow for accessing reports
- Created shortcuts links for direct access to the reports, this way the barber will not get lost.
- Taught the barber and all his employees on how to use the system.

## Outcome
The system was successfully configured to track sales per employee. This allowed the business to accurately calculate commissions and eliminated the need for manual tracking, improving efficiency and transparency.

## Tools Used
- Wix POS  
- Wix Dashboard (Analytics & Roles Management)

## Lessons Learned
This project highlighted the importance of proper user configuration in POS systems and reinforced my ability to troubleshoot real-world technical issues and communicate solutions to non-technical users.
