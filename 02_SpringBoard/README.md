# SpringBoard Course

This section will be dedicated to documenting my progress for [this course](https://www.springboard.com/learning-paths/cybersecurity-foundations/learn/) from `springboard.com`.
The reason I started this course is because I was reading [this article](https://www.springboard.com/blog/cybersecurity/how-to-learn-cybersecurity/) about how to actually progress when looking for a job in cybersecurity.

## Jobs
From the start, the course keeps recommending we compare different cyber security jobs and choose the ones that appeal the most.
This is so that we know what to look for when getting a job but also what material to study as there is a large range of different subjects.

The ones that stand out to me are:
- **Malware Analyst**: Analysing malicious software to understand the threat, the entrypoint, exploits and the nature of it.
- **Chief Information Security Officer**: Leading staff in identifying, developing, implementing and maintaining processes accross an organization. Responsible for information-related compliance.
- **Cyber Defense Analyst**: Primary security contact (mostly for small to mid size organizations), must deal with engineering and architecture, incident triage and response, security toll administration and more.
- **Security Engineer**: Designing, implementing and tuning an effective combination of network-centric and data-centric controls to balance prevention, detection and response.
- **Pen Tester**: Penetration testing to probe the security integrity of a company's defenses by evaluating the attack surface of all in-scope vulnerable web-based services, client-side applications, server-side processes and more.

## Certifications
Once a rough idea of the job / domain I want has been decided, I need to know what can get me there.
An important part of actually getting a job in cybersecurity is having the correct certification.

These are a few examples of the ones I think could be useful to me:
- **CompTIA Security+**: General cybersecurity certification that tests that you have "the baseline skills necessary to perform core security functions and pursue an IT security career".
- **GIAC Security Essentials (GSEC)**: Also a general certification, this one seems to have more hands on parts to test for practical skills. GIAC also have lots of other certifications.
- **ISACA Cybersecurity Fundamentals**: A certification supposedly very good for students and recent graduates to show that you have demonstrated you're understanding of the basic principles.

## Threats
Obviously there are many different types of attack and other cybersecurity threats out there. This is one of the reasons why there are so many different jobs one can choose in cybersecurity.

Here are a few of the main threats currently.

### Phishing
This is probably the most well known one especially outside of the computer science community.

Phishing is the act of tricking people into clicking on or downloading malicious messages/software.
The goals of phishing vary depending on the type of attack.

There are also different types of phishing including:
- **Spear-phishing**: phising that is tailored to a specific demographic or company
- **Whaling**: targets top-level executive
- **Smishing**: just like phishing but through SMS
- **Search engine phishing**: pushes fake results to the top of search engines using SEO (search engine optimization)
- **Vishing**: attacks through phone calls to obtain information

### Ransomware
This threat is one of the most effective ones when it comes to paralizing the victim.
It is extremely hard to deal with and most of the time the users that were the direct victims do not know how to handle the situation.

The way it works is the attacker uses various mechanisms to block the user's access to it's files and software and then demands a financial compensation to restore the access.
This obviously relies on social engineering tricks especially to do with the user's distress.

What makes this a hard problem to deal with is that the attacker can never be trusted. Even if the victim was to pay what was demanded there is no garantee that they will retrieve access to there files.
There are pretty much only three options when it comes to dealing with this type of attack:
- Pay the ransom and hope to get the access back
- Somehow remove the malware
- Wipe all the data to avoid the attacker getting a hold of it, then try and restore from backups

### Malware
Malware is a quite vague term that describes many different types of attack. It mostly describes the way in which the attack is perpetrated.

Malware is software who's goal is to cause problems or aquire data most of the time.
This includes many types of programs such as adware, spyware, viruses, worms, ransomware, trojans,...

These types of attacks rely on the fact that end users are often not properly trained in detecting these programs and that in general people trust uncertain systems.
The most often these attacks get access to a larger system because a user opened an unsafe document or clicked on dubious links.

### Data Breach
A data breach is also farely vague as it simply means that information from a closed system was accessed from the exterior.

This is often what happens with badly protected systems and it is normally to gain money that these attacks happen.

The major problem linked to these types of attacks is the loss of image of the company that suffered the breach. They then need to spend lots on fixing the original problem but also to protect their image.

### Distributed Denial of Service
A DDoS attack involves an attacker sending very large amounts of traffic to a system to paralize it, it is a DDoS instead of a DoS attack when the traffic comes from lots of different places and not a single IP.

These attacks render the system incapable of fulfilling it's normal tasks as it has two many other requests coming in.
This leads to unusually high amounts of downtime for the system and therfore causes severe monetary losses for the company.

### Man in the Middle attack
MitM attacks involve intercepting network traffic and potentially harmfully modifying it.

This is often achieved by pretending to be a normal part of the network for example a router in order to spy on conversations or modify requests.

This particularly problematic with the increase in home office working as this new type of communication needs to be incrypted to insure nothing can intercept and modify the data.

### Insider threats
Insider threats, although not very common, can be highly problematic. These imply that an attack or data compromise was perpetrated from someone who already had access to the system.

These threats are not always intentional as they can be due to user errors. They are also not always done by employees but instead by anyone who has legitimate access (e.g. third-party contractors).

Various types of insider threats exist:
- Employees duped by things like phishing
- Employees not following company security guidelines
- Insider who purposely uses their access to rechieve and sell private data
- Unhappy employee who's goal is to disrupt the company integrity
- Contractor who misuses your services and accidently compromises the security of your data

Detecting these types of attack is complicated as the attacker does not need to breach the system's security as they already have access to sensitive data.
There are some ways of finding out something is going on though:
- Odd login hours
- Access to non job related data
- Downloads of large amounts of information
- Copying data to personal devices
- Creation of accounts with different authorizations

### Threat actors
There are various different types of actors and they have their own goals and or motivations.

The majority of the actors are motivated by monetary gain.

Other more specific threat actors include:
- **Cyber terrorists**: their goal is usually to harm a country's infrastructure
- **Advanced persistent threat actors**: mostly working with or for their government
- **Hacktivists**: generally don't do it for money but for more political reasons
- **Insiders**: internal actors who can do direct damage without having to breach the system
- **Script kiddies**: non professional actors who do not have the necessary knowledge/skills to carry out a full scale attack

### Counter measures
There are multiple proactive steps that companies can take to protect themselves from different data breaches.
Here are a few of them:
- Educate employees on the threats (e.g. phishing training)
- MFA (Multi Factor Authentication)
- Network monitoring
- Intrusion detection/prevention: automated tools that contain potential threats

## Security technologies and techniques
In this section we see the different ways in which we can protect against attacks.

### Defense in depth
```
"Defense in depth is a security strategy in which multiple security tools, mechanisms, and policies are deployed in tandem on the assumption that if one fails, another will hold."
```

Systems that comply with defense in depth build every part of the system assuming the security will fail and therefore have multiple layers of protection.

This strategy does not only imply multiple layers of security but also an entire mindset of how to deal with attacks.
For example it would encompass the fact of planning the aftermath of an attack or even the procedure to combat an ongoing attack.

The elements constructing defense in depth are the following:
- **Administrative controls**: organizational strategies for protection
- **Physical controls**: physical security measures (e.g. access control, security guards,...)
- **Technical controls**: the various layers mentionned before and are detailed below

#### Layers
- **Network**: outer protection of the network with things like the firewall and breach detection systems which scan the network
- **Anti-malware**: malicious software detection that is used after the firewall has been breached
- **Behavior analysis**: analysing behavioral patterns to tell if the user or process is behaving oddly
- **Data integrity**: tools to deal with data corruption
