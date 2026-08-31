# Security Policy

This is the default security policy for all repositories in the `hephaestus-build` organization.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

When your finding concerns a specific repository, use that repository's own **Report a
vulnerability** button (under its *Security* tab) to open a
[GitHub private vulnerability report](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
there — it keeps the report confidential, routes it to the right maintainers, and credits you in the
resulting advisory. If you cannot use GitHub, or the finding spans the organization rather than one
repository, email [felixtj.dietrich@tum.de](mailto:felixtj.dietrich@tum.de) with the subject
"Hephaestus Security Vulnerability Report".

Please include as much as you can:

- The affected repository and component (application server, webapp, webhook receiver, deployment configuration, ...)
- Steps to reproduce, ideally with a proof of concept
- The impact — what an attacker could achieve
- Any suggested fix or mitigation

## What to Expect

Security reports are triaged before other work.

- **Initial response within 14 days.**
- We follow **coordinated disclosure**: please give us time to ship a fix before disclosing publicly. If we cannot agree on a timeline, we treat **90 days** from your report as the default disclosure date, shortened when a vulnerability is being actively exploited.
- Confirmed vulnerabilities are fixed as soon as feasible and published as GitHub Security Advisories on the affected repository. You are credited unless you prefer to stay anonymous.

We do not run a bug bounty program.

## Scope

In scope: the code in this organization's repositories. We are particularly interested in findings
that affect **tenant isolation**, **webhook ingress**, **credential handling**, or the **agent
sandbox**.

Out of scope:

- Vulnerabilities in third-party dependencies without a Hephaestus-specific exploit path — report those upstream
- Denial-of-service, volumetric attacks, and scanner output without a demonstrated impact
- Social engineering or phishing of maintainers or users
- Testing against deployments you do not operate — **do not test against our production instances**; run your own

## Safe Harbor

We consider good-faith security research conducted under this policy to be authorized, and we will not pursue or support legal action against you for it. If a third party takes action against you for such research, we will make our authorization known. In return, only access the minimum data needed to demonstrate an issue, and do not degrade, disrupt, or destroy data or service.

## Supported Versions

Hephaestus is pre-1.0 and released continuously from `main`; **only the latest release is supported**. There are no maintenance branches or backports.
