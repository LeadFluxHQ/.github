# Security Policy

LeadFlux triggers real phone calls from real SIMs on real devices, handles lead and contact data for sales teams, and processes billing through Stripe. We treat security reports as high priority regardless of which repo they land in.

## Reporting a vulnerability

Do not open a public issue for a security vulnerability.

Email security@leadflux.in with:

- A description of the vulnerability and its impact
- Steps to reproduce, or a proof of concept
- The affected repo, version or commit, and environment
- Your assessment of severity, if you have one

You will get an acknowledgment within 48 hours. We aim to give you a status update within 5 business days.

## Disclosure process

1. You report privately.
2. We confirm and triage. We may ask follow-up questions.
3. We develop and test a fix.
4. We release the fix and, once users have had time to update, publish an advisory.
5. We credit you in the advisory, unless you ask to stay anonymous.

We ask that you give us a reasonable window to fix an issue before any public disclosure — 90 days is our standard, shorter for actively exploited issues.

## Scope

In scope:
- leadflux-sdk-js, leadflux-sdk-python, leadflux-webhooks
- docs and roadmap sites, for issues like XSS, auth bypass, secret leakage
- The LeadFlux API and dashboard

Out of scope:
- Denial of service via volumetric traffic
- Social engineering against LeadFlux staff or customers
- Issues that require physical access to a rep's Android device

## Supported versions

SDKs — latest major: supported.
SDKs — previous major: security fixes only, for 6 months after the next major release.
SDKs — older: not supported.
Hosted platform: always latest, no versioning.

## Bug bounty

We do not currently run a paid bug bounty program. We credit researchers publicly and will discuss compensation for high-severity, well-documented reports on a case-by-case basis.
