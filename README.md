# DDS Network Doctor

> Evidence-based diagnostics for Fast DDS / ROS 2 networking problems.

🚧 **Early-stage market validation**

DDS Network Doctor is a proposed offline diagnostic tool for engineers troubleshooting Fast DDS / ROS 2 communication and discovery problems.

The project is currently validating whether there is enough real-world demand to justify development.

## Problem we want to investigate

Typical cases include:

- ROS 2 / Fast DDS participant discovery failures
- Multi-NIC, VLAN, multicast or cross-subnet communication issues
- Communication failures after IP/network changes
- Fast DDS XML transport, interface or locator configuration problems
- Time-consuming troubleshooting involving RTPS packet captures and XML profiles

## Proposed direction

The initial concept is a local CLI that can analyze Fast DDS XML profiles, RTPS PCAP captures, and Linux network/interface information, then produce an evidence-based diagnostic report with possible root causes and remediation suggestions.

**No product release is promised yet. The first goal is to validate the problem and willingness to pay.**

## Feedback

If you work with Fast DDS, ROS 2, RTPS or Linux networking, please share:

1. What communication/discovery problems are hardest for your team to diagnose?
2. How much engineering time do they typically consume?
3. Would an offline diagnostic tool be useful?
4. Would your organization pay for a tool that demonstrably reduces troubleshooting time?

See docs/market-research.md for the current research questions.

## Status

- [x] Repository created
- [ ] Collect real-world problem cases
- [ ] Validate willingness to try a prototype
- [ ] Validate willingness to pay
- [ ] Build MVP only if demand is demonstrated

Fast DDS and ROS 2 are referenced for compatibility/context; this project is independent and is not an official product of their respective projects.
