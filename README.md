OPEN-SOURCE SECURITY
TOOLS



WHAT ARE OPEN-SOURCE TOOLS

Tools that are free for open-source projects in each
of the above categories are all listed one by one in
the upcoming slides.

Open source Security tools are free resources used
for security testing purposes




REQUIREMENT FOR SECURITY TESTING

What is security testing or penetration testing
and why they are needed?

Security testing also known as penetration testing is
a a pro-active way of testing the security of the
organization’s network, web, applications and all IT
resources.

Computer security experts, also known as white
hackers are using these types of tools to be able to
detect , and address security vulnerabilities in a
computer application.

You could actually say that penetration testing is
much like hiring security consultants to attempt a
security attack on a secure facility to find out how
real hackers might go about doing the actual thing.




TYPES OF OPEN-SOURCE CYBERSECURITY TOOLS FOR SECURITY
TESTING


Password protection tools

Network scanning and security tools

Web server security tools

Code scanning tools

DB Security tools

Intrusion Detection tools

Vulnerability assessment tools

Security monitoring and logging tools

OWASP tools


PASSWORD MANAGERS


What are password managers and why they are
needed?

These tools provide encrypted digital vaults that are
developed to store secure password login information
which is used for accessing apps and accounts on mobile
devices, websites, and also other devices.

Along with keeping identity, credentials, and sensitive
data safe, the password manager can generate strong,
and unique passwords and ensure that users aren’t using
the same password in so many different places (password
generation really comes in handy when users are unable
to come up with yet a matchless password)

Password managers offers to keep multiple passweord
safe and reduces the password reset requests for IT
support personnel


Here are a few lists of some open-source password
managers

KeePass (OS)

Passbolt (OS)

Psono (OS)

Password Safe (OS)

Bitwarden (OS)




WELL-KNOWN NETWORK SECURITY TESTING TOOLS

Nmap

For reconnaissance, this is the preferred opensource tool, it can quickly scan large networks and runs on all
major OSes.

Wireshark

This is a popular network protocol analyzer that is supported on all the main OSes. It helps with live
capture, decryption support and offline analysis for every key network protocol

Jok3r

Another framework for network infrastructure and web pen testing is Jok3r which is a collection of more
than 50 open-source tools and scripts

Legion

Legion is an open source, easy-to-use, super-extensible and semi-automated network penetration testing




WEB SERVER SECURITY SCANNING TOOLS

A web application security scanner is a software which performs automatic black-box testing on a web application and identifies
security vulnerabilities. There are plenty of tools, but listing some of the commonly used tools for web applications.

Zed Attack Proxy

OWASP's Zed Attack Proxy (ZAP) scans web applications for vulnerabilities..

Nikto

Nikto is an Open Source (GPL) web server scanner which performs comprehensive tests against web servers for multiple items, including testing for over
6700 potentially dangerous files/programs, checks for outdated versions of servers, and version specific problems

Wfuzz

Developed in Python, Wfuzz is popularly used for brute-forcing web applications. The open-source security testing tool has no GUI interface but only
command line

Wapiti

This is used to check web applications for security vulnerabilities, Wapiti performs black box testing. As it is a command-line application, it is important to
have a knowledge of various commands used by Wapiti.

W3af

w3af is an open-source web application security scanner. The project provides a vulnerability scanner and exploitation tool for Web applications. It
provides information about security vulnerabilities for use in penetration testing




ADDITIONAL SECURITY TOOLS

Code Scanning tools checks for the quality of the code and checks of security issues before it is deployed into the server

SonarQube

SonarQube is an open-source platform developed by SonarSource for continuous inspection of code quality to perform automatic reviews
with static analysis of code to detect bugs and code smells on 29 programming

Horusec

It performs code scanning that will check if there is any vulnerability or security issue

DB security tools checks for vulnerabilities with database servers.

Sql

SQLMap is a tool used for the automated exploitation of SQL injection vulnerabilities. We can use SQLMap to test websites and databases
for vulnerabilities and exploit those vulnerabilities to take over the database.

NoSQL

NoSQLMap is an opensource Python tool designed to audit for as well as automate injection attacks and exploit default configuration
weaknesses in NoSQL databases, as well as web applications using NoSQL in order to disclose data from the database. The current project
goals are to provide a penetration testing tool to simplify attacks on MongoDB servers and web applications as well as proof of concept
attacks to debunk the premise that NoSQL applications are impervious to SQL injection.




INTRUSION DETECTION TOOLS – HIDS AND NIDS


HIDS stands for Host-based intrusion detection system.
HIDS basically represents an application monitoring a
computer or network for various suspicious activities.

HIDS work by logging the suspicious activity, and also
reporting it to the administrators managing the devices or
networks.

OSSEC is short for Open Source Security Event Correlator.
This established and reputable solution is a free and
open-source host-based intrusion and one of the popular
choices

Wazuh is another open-source monitoring solution for
integrity monitoring, incident response, and compliance.

Opensource Tripwire is a free and open-source host-based
detection system. The company offers a commercial solution
too, but free version is also available

Network-based IDS (NIDS), analyze network traffic for
any intrusion and produce alerts to system administrators and
network security engineers.

NIDS complements HIDS to enforce detection–both
signature-based and anomaly-based – and acts as a safeguard
to monitor traffic going to and from your organization’s
different network devices.

Snort - Snort is a free and open-source network-based
intrusion detection system maintained by Cisco Systems.

Suricata - A network-based intrusion detection system which
provides real-time intrusion detection and prevention
capabilities in addition to features for monitoring network
security.

Zeek - Network Security Monitor is also free and
open-source




VULNERABILITY ASSESSMENT SCANNER - OPENVAS

OpenVAS

In the past, it was undecided that suggesting to educational
institutions the OpenVAS open-source vulnerability scanner.
Why? Not because it isn’t a great tool. In the contrary, it’s
been one of the go-to options since it forked from Nessus
back in the day. The reason with that being is because,
historically, installing it and getting into an operational state
can be complicated. Nowadays though, because of
containerization environments like Docker (take a look at the
previous slide), you can stand up a fully functional instance (or
nearly so) with just one command. For those organizations
that need to boost their vulnerability assessment capability in
a touch (and who doesn’t?), using OpenVAS – particularly
pre-packaged containers – is well within the reach of even
those organizations with limited technical staff.



MONITORING AND LOG MANAGEMENT - SECURITY ONION –

Security Onion is a multi-purpose free
and open source Linux distribution for
intrusion detection, security monitoring,
and log management.

The first tool on the list is an open-source Linux distribution that targets
security monitoring. It comes with a host of built-in tools (for example.,
Snort, Suricata) designed to help you monitor a user's environment for
security-relevant activity at multiple levels of the stack. One of the
advantages that using the distribution has, over just installing and using
the underlying toolset directly, is that Security Onion a term called
helpful setup wizard. Even if the organization doesn’t have an army of
security operations staff, the tool allows users to still stand up a
full-featured monitoring solution in relatively little time. Also, because
campus environments can be both wide, and workable (for example as
learning-oriented environments might be set up for particular purposes),
using this tool has the dominance of a “drop-in”, short-term monitoring
solution for a momentary environment without incurring additional
hardware or licensing costs.



INTRODUCTION – OWASP SECURITY TOOLS

The OWASP’s (Open Web Application Security Project) operation is to help the world improve the security of its
software. One of the best ways OWASP can do that to help Open-Source developers to improve the software they are
creating that everyone else relies on. By itself, the following lists of automated vulnerability detection tools that are free
for open-source projects that have been gathered together here to raise awareness of their availabilities.

It would be best to encourage Open-Source projects to use the following types of tools to be able to improve the security
and quality of their code:

Static Application Security Testing (SAST) Tools

Dynamic Application Security Testing (DAST) Tools (primarily meant for web apps)

Interactive Application Security Testing (IAST) Tools – (primarily meant for web apps and web APIs)

Keeping Open-Source libraries up to date (this is meant to avoid using components with unknown vulnerabilities
(OWASP Top 10-2017 A9))

Static code quality tools



SAST TOOLS

OWASP already keeps a page of known SAST tools:
Source Code Analysis Tools, which includes a list of
those that are “Open-Source of Free Tools of this
type”. Any such tools could certainly be used.

GitHub code scanning – It is free for open static
analysis service that uses GitHub Actions and
CodeQL to scan public sources on GitHub. This all
supports C/C++, C#, Ruby (beta), Java,
JavaScript/TypeScript, Python, and Go (click this link
https://codeql.github.com/docs/codeql-overview/sup
ported-languages-and-frameworks/ for more info)



DAST TOOLS

If your project has a web application component, then it is
recommended that running automated scans against it to look
for vulnerabilities. OWASP maintains a page of known DAST
tools, and the License column on this page indicates which of
those tools have free capabilities. The most primary
recommendation is to use one of these listed below:

OWASP ZAP – This is a full featured free and open source
DAST tool that includes both automated scanning for
vulnerabilities and tools to assist expert manual web app pen
testing.

Stack Hawk - 2 Stack Hawk is commercially used to support
DAST tool built on OWASP ZAP and it is optimized to run in
CI/CD (almost every CI is supported) to test web applications
during development and in CI/CD. The Stack Hawk platform
allows a user to manage findings over time in different
environments.



IAST TOOLS

IAST tools are normally pitched to analyze web
applications and Web APIs, but that is vendor specific.
There may be IAST products that can perform good
security analysis on non-web applications as well.

Contrast Community edition (CE) – Fully featured
version for 1 app and up to 5 users (some Enterprise
features disabled). Contrast CE supports Java and
also .NET only.

API web scanners

For tools which are API specific, it is recommended to
refer to the OWASP community API security tools page
as it will vary for each use case.



CODE QUALITY TOOLS

Quality has a significant connection to security. As
such, it is recommended that open-source projects also
consider using good code quality tools. There are a few
tips that we should be aware of, and that are:

Spot Bugs – Open-source code quality tool for Java

This is the active fork for Find Bugs, so if users use Find
Bugs, they should switch to Spot Bugs

Spot Bug users need to add the Find Sec Bugs plugin
(https://find-sec-bugs.github.io/) to their Spot Bugs
setup, as it is meaningly improving on the very basic
security checking native to Spot Bugs.



