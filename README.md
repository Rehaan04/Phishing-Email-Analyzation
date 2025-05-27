# Phishing-Email-Analyzation
The Objective of this demonstration is to identify phishing characteristics in a suspicious email sample.

# Steps Followed
1) Obtained a fake email sample impersonating contoso corps IT help desk team.
2) Examined sender's email address 
3) Analyzed email header for discrepancies using free online tool 'mxtoolbox.com'.
   - If the SPF or DKIM shows 'FAIL' message, IT means the sending server is not authorized or the message is not signed indicating a spoofed message.
4) Identified suspicious links or attachments in the message.
5) Looked for urgent or threatening language 
   - in the above example,statements such as 'It is crucial that all employees update their system immediately' and
   - 'Failure to do so will result in being locked out of your system'
6) Hovering over the link text 'Update Now' will show you a completely different domain indicating that it is a phishing attempt.
7) Verified the presence of spelling and grammer errors.
8) Summarized the phishing traits found in the above mail:
   - SPF/DKIM authentication FAIL
   - Presence of urgent and threatening language
   - Suspicious and different link text destination

# Conclusion
In conclusion,the above email exhibits multiple high risk phishing indicators and should be reported immediately.
