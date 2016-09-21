# Responsible Disclosure Policy

Coderdojo Foundation Responsible Disclosure Policy

We take the security of our systems seriously, and we value the security community. The responsible disclosure of security vulnerabilities helps us ensure the security and privacy of our users.

**Guidelines**  

We require that all researchers:
* Make every effort to avoid privacy violations, degradation of user experience, disruption to production systems, and destruction of data during security testing;
* Perform research only within the scope set out below;
* Use the identified communication channels to report vulnerability information to us; and
* Keep information about any vulnerabilities you’ve discovered confidential between yourself and the Coderdojo Foundation until we’ve had 90 days to resolve the issue.


If you follow these guidelines when reporting an issue to us, we commit to:
* Not pursue or support any legal action related to your research;
* Work with you to understand and resolve the issue quickly (including an initial confirmation of your report within 3 working days);
* Recognize your contribution on our Security Researcher Hall of Fame, if you are the first to report the issue and we make a code or configuration change based on the issue.


**Scope**  
* \*.coderdojo.com

**Out of scope**  
Any services hosted by 3rd party providers and services are excluded from scope. These services include but are not limited to:
* Sendgrid
* LearnUpon
* Twilio
* AWS
* Blacknight

In the interest of the safety of our users, staff, the Internet at large and you as a security researcher, the following test types are excluded from scope:
* Findings from physical testing such as office access (e.g. open doors, tailgating)
* Findings from applications or systems not listed in the ‘Scope’ section
* UI and UX bugs and spelling mistakes
* Network level Denial of Service (DoS/DDoS) vulnerabilities

Things we do not want to receive:
* Personally identifiable information (PII)

**How to report a security vulnerability?**  
If you believe you’ve found a security vulnerability in one of our products or platforms please send it to us by emailing security@coderdojo.com. Please include the following details with your report:

* Description of the location and potential impact of the vulnerability;
* A detailed description of the steps required to reproduce the vulnerability (POC scripts, screenshots, and compressed screen captures are all helpful to us); and
* Your name/handle and a link for recognition in our Hall of Fame.

If you’d like to encrypt the information, please use our GPG Key.
```
-----BEGIN PGP PUBLIC KEY BLOCK-----
Version: GnuPG v2

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
0NFwkKNjtDJogMUhgO0=
=WKyF
-----END PGP PUBLIC KEY BLOCK-----
```
