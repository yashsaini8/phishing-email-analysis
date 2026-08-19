Headers
======================================
Date:Tue, 31 Oct 2023
Subject: Your account has been flagged for unusual activity

To: dderringer@mighty-solutions.net
From: social201511138@social.helwan.edu.eg

Return-Path: social201511138@social.helwan.edu.eg

Sender IP: 40.107.22.60
Resolve Host: mail-am6eur05on2060.outbound.protection.outlook.com

Message-ID: JMrByPl2c3HBo8SctKnJ5C5Gp64sPSSWk76p4sjQ@s6



URLs
======================================
hxxps[://]0[.]232[.]205[.]92[.]host[.]secureserver[.]net/lclbluewin08812/



Description
======================================
This Email is claiming to be from "Microsoft" and it is asking the recipient to re-verify their account.

It claims that the account has been disabled due to unusual activity.

Their are several indications of urgency within the content of this email, as it claims the account will completely suspended by "November 1, 2023" if the account is not verified by then.



Artifact Analysis
======================================
Sender Analysis:
Although claiming to be from Microsoft, the FROM address clearly indicates a mailbox originating from an unrelated domain (social.helwan.edu.eg). 
Additionally, the Return-Path and Received Headers indicate that this email originated from a compromised university account (social201511138@social.helwan.edu.eg) routed through Microsoft's Exchange Online infrastructure (40.107.22.60).

URL Analysis:
After performing a URL reputation check using VirusTotal, the URL within the call to action button of this email was found to be malicious, as it redirects to a phishing website.
It appears to be hosting a credential capture page, that when submitted, will log and steal the credentials of any victim.



Verdict
======================================
Due to the original sender being unaffiliated with Microsoft, this email is a clear impersonation and spoofing attempt.
After analyzing the URL contained in the Email's call to action, it was flagged on Virustotal to be malicious.
As a result of this analysis this email is determined to be suspicious.



Defense Actions
======================================
After performing a message trace, no other users within the organization recieved an email from this sender or with this subject line.

To prevent the malicious sender from sending any other  email to the organization, I have blocked the "social201511138@social.helwan.edu.eg" email address on the email gateway.
