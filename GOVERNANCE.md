# Pulseq Organization Governance

## Purpose

The Pulseq GitHub organization provides a shared home for open tools, specifications, implementations, and community activities related to Pulseq-based MRI sequence description, programming, validation, and exchange.

The purpose of this governance document is to support transparent decision making, distributed stewardship, sustainable software practices, and coordination across the Pulseq ecosystem, including MATLAB Pulseq, PyPulseq, and related projects.

## Governance principles

Pulseq repositories should follow these principles:

1. **Open development**  
   Technical discussions, feature proposals, bug reports, critiques, and pull requests should occur publicly on GitHub whenever possible.

2. **Distributed stewardship**  
   No repository should depend on a single individual, laboratory, institution, vendor, or implementation group.

3. **FAIR software practices**  
   Pulseq software should be Findable, Accessible, Interoperable, and Reusable through clear repository metadata, documentation, licensing, releases, versioning, citation information, and machine-readable configuration where appropriate.

4. **Cross-implementation coordination**  
   MATLAB Pulseq, PyPulseq, and related tools should coordinate on file format compatibility, validation, examples, documentation, release planning, and specification changes.

5. **Transparent decision making**  
   Significant technical, governance, access-control, repository-stewardship, or release-process decisions should be documented through GitHub issues, discussions, pull requests, meeting notes, or decision records.

6. **Consensus before major stewardship changes**  
   Repositories should not be moved, renamed, archived, transferred, substantially restructured, or have their governance model changed without prior discussion and consensus among organization owners and affected repository maintainers.

7. **Reviewable development**  
   Development should favor small, focused, reviewable pull requests. Large changes should be preceded by an issue, discussion, design note, or staged implementation plan.

8. **Community-connected development**  
   Community-led initiatives from workshops, hackathons, user meetings, educational activities, and scientific use cases should be recorded and reviewed as potential inputs to roadmaps, documentation, validation priorities, and future releases.

## Organization roles

The Pulseq organization should use teams to distribute responsibility.

Recommended teams include:

- `org-owners` — organization owners responsible for continuity, access stewardship, governance, and security-sensitive organization settings.
- `matlab-pulseq-maintainers` — maintainers responsible for MATLAB Pulseq development, review, testing, documentation, and releases.
- `pypulseq-maintainers` — maintainers responsible for PyPulseq development, review, testing, documentation, and releases.
- `spec-maintainers` — cross-implementation maintainers responsible for Pulseq specification compatibility, examples, validation, and interoperability.
- `community-contributors` — contributors involved in issues, discussions, workshops, examples, documentation, education, testing, and community initiatives.

Repository access should follow the principle of least privilege while ensuring continuity. Critical repositories should have more than one maintainer and more than one person able to support continuity.

## Decision process

Routine repository changes, such as bug fixes, documentation updates, tests, examples, and small non-breaking features, may be handled through normal pull request review.

Significant changes should be preceded by a GitHub issue, discussion, design note, or proposal. Significant changes include:

- API-breaking changes
- Pulseq file format or specification changes
- MATLAB/Python interoperability changes
- release-process changes
- package-publishing changes
- major dependency or build-system changes
- repository moves, renames, archival, or transfers
- maintainer or administrator access changes
- license changes
- large pull requests that are difficult to review as a single unit

Where consensus is not immediately available, maintainers should seek a staged plan, smaller pull requests, or a documented decision process.

## Repository stewardship

Each major repository should identify its active maintainers and expected review process. Maintainers are responsible for:

- reviewing pull requests
- triaging issues
- guiding releases
- improving documentation
- supporting tests and examples
- coordinating with related Pulseq implementations
- encouraging constructive community participation

Maintainer lists should be reviewed periodically. Inactive maintainers may be moved to emeritus or advisory status after discussion.

## Pull request expectations

Pull requests should be as small and focused as practical. Large changes should be split into reviewable stages when possible.

A large or architectural pull request should include:

- motivation and scope
- affected repositories or implementations
- backward-compatibility considerations
- testing and validation plan
- documentation impact
- release impact
- migration path, if needed

Maintainers may ask contributors to split large pull requests into smaller pieces before review.

## Community meetings

The Pulseq ecosystem should hold at least three structured meetings each year:

1. **Owners meeting**  
   A meeting of Pulseq organization owners to review organization-level governance, access rights, repository stewardship, long-term sustainability, security, and continuity planning.

2. **Maintainers meeting**  
   A meeting of MATLAB Pulseq and PyPulseq maintainers to review development priorities, release plans, specification alignment, compatibility issues, open pull requests, testing, documentation, package distribution, and cross-language feature coordination.

3. **Developers and community meeting**  
   An open or broadly invited meeting for contributors, users, developers, and community members to discuss feature requests, barriers to contribution, educational needs, research and clinical use cases, implementation concerns, and community-led initiatives.

These meetings should include representation from both the MATLAB and Python implementations whenever possible.

The meetings may be held as part of a Pulseq workshop, hackathon, conference satellite session, or similar community event. For example, a PyPulseq workshop hosted by Sairam Geethanath could serve as an initial venue, with owners, maintainers, and developers/community meetings held on separate days. However, the preferred long-term model is to distribute these meetings across the year.

Meeting outcomes should be summarized publicly when appropriate, including decisions, action items, proposed roadmap changes, maintainer or access updates, and unresolved issues requiring further input.

## Annual review

At least once per year, the organization should review:

- active maintainers and access rights
- repository ownership and stewardship
- open issues and pull requests
- release cadence
- MATLAB/Python/specification alignment
- package publishing permissions
- branch protection and security settings
- FAIR software practices
- community feedback and workshop outcomes

The goal is to ensure that Pulseq remains open, sustainable, technically rigorous, and community responsive.