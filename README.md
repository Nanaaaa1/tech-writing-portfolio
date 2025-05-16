# tech-writing-portfolio
Samples of technical documentation by Nana Adu-Abankro
= Technical Writing Portfolio: Infrastructure & Support Docs
Nana Adu-Abankro
:revdate: 2023-01-15
:icons: font
:toc:

== Overview

This repository contains real-world technical documentation examples modeled after tasks performed in a production support environment. All examples are written in AsciiDoc format using a Docs-as-Code workflow to reflect industry-standard authoring.

== Key Use Cases

* FedEx application support using SuperPuTTY/SSH
* Jenkins-based CI/CD pipeline documentation
* Error log inspection, triage, and incident response
* System service restart procedures
* UPS testing for internal tools (ISS)
* Application checkout & log validation steps

== Docs-as-Code Stack

* AsciiDoc for structured technical writing
* Git for version control
* Structured in folders by use case (logs, service, test, etc.)

== 📘 Documentation Index

|===
| Document | Purpose

| link:check-error-logs.adoc[check-error-logs.adoc] | Guide for identifying and interpreting system/application errors
| link:service-restart-guide.adoc[service-restart-guide.adoc] | Restart and shutdown procedures for internal SWAK applications
| link:ups-test-guide.adoc[ups-test-guide.adoc] | Step-by-step UPS testing for ISS
| link:jenkins-app-checkout.adoc[jenkins-app-checkout.adoc] | Instructions for using Jenkins for application checkout
| link:incident-template.adoc[incident-template.adoc] | Incident handling and documentation structure
|===

== How to Use

Clone the repository and open `.adoc` files using:

[source, bash]
----
git clone https://github.com/<your-username>/tech-docs-fedex.git
cd tech-docs-fedex
code README.adoc
----

Use any AsciiDoc previewer (like the AsciiDoc plugin for VSCode) or convert to HTML via Asciidoctor.

== Sample Topics Covered

* SSH log inspection with `journalctl`, `syslog`, and app logs
* Restarting services with `systemctl` and validating results
* Jenkins automation usage for controlled deployments
* Realistic examples and commands used in FedEx support scenarios

== Contact

If you'd like to collaborate or want me to expand this portfolio, feel free to contact me on LinkedIn or GitHub.
