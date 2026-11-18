# Market Research

## Goal

Determine whether engineers and companies have a recurring, painful problem around diagnosing Fast DDS / ROS 2 networking issues that is valuable enough to support a paid developer tool.

## Research questions

### 1. Problem frequency

- What failures occur repeatedly?
- Discovery failure vs. data-plane failure?
- Multi-NIC / VLAN / multicast / IP mobility?
- QoS incompatibility?
- Performance degradation?

### 2. Current workflow

What tools are currently used?

- Wireshark
- ros2 doctor
- DDS vendor tools
- Fast DDS logs/statistics
- Custom scripts
- Source-code debugging

### 3. Pain level

Ask:

- How long does a typical incident take to diagnose?
- How many engineers are involved?
- Is the issue reproducible?
- Does it happen in customer/production environments?

### 4. Buying signal

Strong signals:

- We have this problem now.
- Can I send you a PCAP/XML to test?
- When can I try it?
- How much would it cost?
- We need this for multiple engineers/projects.

Weak signals:

- Likes/stars only
- General agreement that the idea is interesting
- Requests for many features without willingness to test or pay

## Initial hypothesis

The first candidate product is an offline Discovery/Network Doctor.

Inputs: Fast DDS XML, RTPS PCAP, Linux network snapshot.

Outputs: evidence, suspected root cause, confidence/limitations, suggested remediation, HTML/JSON report.

This is a hypothesis, not a committed product scope.

## 7-day validation target

- 5+ substantive replies
- 3+ people willing to test
- 1+ potential customer willing to discuss paid use
- At least 3 distinct recurring failure patterns

If these signals are not observed, reconsider the product scope before writing substantial code.

## Feedback log

Record only public or explicitly shareable information here. Do not commit customer PCAPs, proprietary XML, source code, credentials, network topology, or other confidential material.
