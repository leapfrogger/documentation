---
description: This is a Beta version of the feature.
---

# Get Started with JFrog SAST

***

### What is JFrog SAST?

<table data-view="cards"><thead><tr><th align="center"></th><th></th><th></th></tr></thead><tbody><tr><td align="center">FAST</td><td>Easy set-up with just a few steps</td><td></td></tr><tr><td align="center"> FOCUSED</td><td>Deep analysis with focus on security issues</td><td></td></tr><tr><td align="center">LOCAL &#x26; SECURE</td><td>Work locally in your environment </td><td></td></tr></tbody></table>

JFrog SAST solution is aimed to allow software developers to hunt, fix, and learn about security issues in their code allowing them to deliver fast, quality code, and reduce issues.

### What does JFrog SAST Scan for?

JFrog SAST scans mainly for specific sensitive operations (DB queries, OS commands, outgoing connection destinations, etc) that can be controlled by an external attacker without proper sanitation injections such as:

* SQL injections
* Command injections
* Code injections
* SSRF&#x20;

It also detects cases when certain APIs (encryption, cryptographic signing, file operations, etc) are used with parameters or under circumstances that render the API use unsafe.

SAST findings are presented in a way that will help you easily locate the vulnerable data flow in your code. The data is represented within an easy-to-use interface that enables you to track each vulnerability in the code and provides the following information per vulnerability:

* **Data Flow Analysis**: Provides information on the overall code flow and the different entry points of the vulnerability up to the execution point of the vulnerability. At JFrog we understand the developer needs to see the entire picture of their code, rather than just providing the specific vulnerability found in the code. With Data Analysis Flow you will be able to follow the entire lifecycle of the vulnerability.
*   **Fix Steps**: To help you fix the security issues, the JFrog security team provides you with detailed fixes and mitigation options for the vulnerabilities. Xray empowers you to make smart choices when creating the mitigation plan and choosing the paths with the highest return on investment.

    Along with the JFrog severity given, you can make informed decisions on what vulnerabilities are a priority to fix. For example, vulnerabilities with low JFrog security severity are considered less risky, as it would be very unlikely to exploit them in the real world, or the impact of the exploitation is low.

### Why JFrog SAST?

#### Discover zero-day vulnerabilities in your code

JFrog SAST is focused on finding 0-day vulnerabilities in your code projects. With a strong balance between FAST execution, QUALITY of scanners, and focusing on SECURITY, JFrog SAST keeps you secured without harming the development process.

#### Early Detection With JFrog Integrations

Incorporate JFrog's scan capabilities into your CI-CD pipeline with JFrog IDE Plugins, JFrog CLI, and Frogbot to continuously monitor your source-code projects and find issues as-early-as-possible in the SDLC.

**Note**: In this version of the Beta, only Visual Studio Code JFrog IDE Plugin is supported.&#x20;

#### Keep Your Source-Code Local and Secured

JFrog SAST is running locally on your developer's workstation --> no source code/data is leaving your premise for the analysis.

***

**Thank you for participating in this Beta. Let us know your feedback regarding this experience**