# The Russia-based actor is targeting organizations and individuals in the UK and other geographical areas of interest.

## OUTLINE OF THE ATTACKS

The activity is typical of spear-phishing campaigns, where an actor targets a specific individual or group using information known to be of interest to the targets. In a spear-phishing campaign, an actor perceives their target to have direct access to information of interest, be an access vector to another target, or both.

### Research and Preparation
Using open-source resources to conduct reconnaissance, including social media and professional networking platforms, Star Blizzard identifies hooks to engage their target. They take the time to research their interests and identify their real-world social or professional contacts.

Star Blizzard creates email accounts impersonating known contacts of their targets to help appear legitimate. They also create fake social media or networking profiles that impersonate respected experts and have used supposed conference or event invitations as lures.

Star Blizzard uses webmail addresses from different providers, including Outlook, Gmail, Yahoo and Proton mail in their initial approach, impersonating known contacts of the target or well-known names in the target’s field of interest or sector.

To appear authentic, the actor also creates malicious domains resembling legitimate organizations.

Microsoft Threat Intelligence Center (MSTIC) provides a list of observed Indicators of Compromise (IOCs) in their SEABORGIUM blog, but this is not exhaustive.

### Preference for Personal Email Addresses
Star Blizzard has predominantly sent spear-phishing emails to targets’ personal email addresses, although they have also used targets’ corporate or business email addresses. The actors may intentionally use personal emails to circumvent security controls in place on corporate networks.

### Building a Rapport
Having taken the time to research their targets’ interests and contacts to create a believable approach, Star Blizzard now starts to build trust. They often begin by establishing benign contact on a topic they hope will engage their targets. There is often some correspondence between attacker and target, sometimes over an extended period, as the attacker builds rapport.

### Delivery of Malicious Link
Once trust is established, the attacker uses typical phishing tradecraft and shares a link, apparently to a document or website of interest. This leads the target to an actor-controlled server, prompting the target to enter account credentials.

The malicious link may be a URL in an email message, or the actor may embed a link in a document on OneDrive, Google Drive, or other file-sharing platforms.

Star Blizzard uses the open-source framework EvilGinx in their spear- phishing activity, which allows them to harvest credentials and session cookies to successfully bypass the use of two-factor authentication.

### Exploitation and Further Activity
Whichever delivery method is used, once the target clicks on the malicious URL, they are directed to an actor-controlled server that mirrors the sign-in page for a legitimate service. Any credentials entered at this point are now compromised.

Star Blizzard then uses the stolen credentials to log in to a target’s email account, where they are known to access and steal emails and attachments from the victim’s inbox. They have also set up mail- forwarding rules, giving them ongoing visibility of victim correspondence.

The actor has also used their access to a victim email account to access mailing-list data and a victim’s contacts list, which they then use for follow- on targeting. They have also used compromised email accounts for further phishing activity.
