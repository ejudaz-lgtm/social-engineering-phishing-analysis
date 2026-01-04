# ParrotPost: Phishing Analysis

## Platform
TryHackMe

## Objective
To analyze a phishing campaign designed to steal user credentials through
client-side techniques while evading detection.

## Phishing Indicators Identified
- Suspicious sender email domain
- Urgent language encouraging immediate action
- Embedded links leading to a fake login page
- HTML and JavaScript used to capture credentials
- Obfuscated client-side scripts

## Attack Technique
The phishing page mimics a legitimate service login interface.
User credentials are captured using client-side scripts and sent to an attacker-controlled server.

## Social Engineering Tactics Used
- Authority (impersonating a trusted service)
- Urgency (account suspension warning)
- Familiar branding and layout

## Defensive Analysis
- Email header analysis can reveal spoofed domains
- JavaScript inspection shows credential harvesting logic
- Lack of HTTPS or invalid certificates indicate phishing

## Mitigation Strategies
- User awareness training
- Email filtering and anti-phishing tools
- Enforcing multi-factor authentication (MFA)
- Browser security warnings

## Conclusion
This exercise demonstrates how phishing attacks exploit human trust
and highlights the importance of defensive awareness and technical controls.

