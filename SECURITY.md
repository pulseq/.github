# Security Policy

## Reporting a vulnerability

If you believe you have found a security vulnerability in a Pulseq repository, please do not disclose it publicly in an issue or discussion.

Instead, contact the relevant repository maintainers or Pulseq organization owners.

When reporting a vulnerability, please include:

- affected repository
- affected version or commit, if known
- description of the issue
- steps to reproduce, if available
- potential impact
- suggested mitigation, if known

## Safety-related scientific functionality

Some Pulseq repositories may contain functionality related to MRI sequence validation, scanner limits, peripheral nerve stimulation estimation, gradient/RF constraints, or other safety-adjacent calculations.

These tools are intended to support research and development workflows. They do not replace local institutional review, vendor safety systems, scanner-specific safety checks, regulatory requirements, or expert review by qualified personnel.

Safety-related changes should receive careful review, include validation where practical, and clearly document assumptions, limitations, and vendor-specific behavior.

## Supported versions

Each repository should document which versions are actively supported. If no repository-specific policy is available, users should assume that only the latest release and current default branch are actively maintained.

## Public disclosure

Maintainers will coordinate public disclosure after a reasonable mitigation plan is available, depending on the severity and scope of the issue.