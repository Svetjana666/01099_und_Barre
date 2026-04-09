# AGENTS - Repository Operations Protocol

## Purpose

This repository documents an OSINT/forensic investigation into AI-generated influencer networks operating with state-level backing and political influence operations targeting German democratic institutions.

## Roles

### Case Owner
- **Responsibility**: Investigation objectives, legal clearances, final assessment
- **Authority**: Final approval on all investigative actions
- **Requirements**: Legal compliance verification, chain-of-custody validation

### Analyst
- **Responsibility**: Execute data collection and analysis according to this playbook
- **Requirements**: Document all steps, maintain artifact logs, follow strict protocols
- **Reporting**: Detailed findings with evidence chain validation

### Reviewer
- **Responsibility**: Verify reproducibility, completeness of evidence chain, data minimization compliance
- **Requirements**: Independent verification of all investigative procedures
- **Standards**: Legal and ethical compliance validation

## Fundamental Principles

### Legality & ToS Compliance
- **Requirement**: All collection must comply with applicable laws and platform Terms of Service
- **Protocol**: No automated scraping, no rate limit circumvention, no unauthorized access
- **Documentation**: Legal basis for each collection action must be documented

### Data Minimization
- **Principle**: Collect only data essential to investigation objectives
- **Implementation**: No mass harvesting of follower/following lists
- **Verification**: Each data point must have specific investigative purpose

### No Automation/Scraping
- **Prohibition**: No bots, no automated extractions, no systematic harvesting
- **Compliance**: Manual collection only, with human oversight
- **Rate Limits**: Strict adherence to platform rate limiting

### Integrity
- **Standard**: Artifacts preserved unchanged (original files untouched)
- **Verification**: Hash verification of all collected artifacts
- **Storage**: Secure, read-only preservation of evidence

### Reproducibility
- **Requirement**: Every step must be reproducible by third parties
- **Documentation**: Complete logs with timestamps and method details
- **Validation**: Independent verification capability

### PII Protection
- **Standard**: Personal data processed only when necessary
- **Implementation**: Redaction/masking for reports, minimal data collection
- **Compliance**: GDPR and privacy law adherence

## Scope (Permitted/Expected Activities)

### Permitted Collections
- **Profile Metadata**: Bio, links, profile images, names, categories, verification status, public highlights
- **Visible Content**: Posts/Reels/Stories (where visible), captions, appropriate comment samples
- **Network Indicators**: Suspicious patterns, recurring contacts (without mass follower/following harvesting)
- **Inauthenticity Indicators**: Username changes, suspicious linktrees, identical captions, bot-typical interaction patterns
- **Account Metadata**: Creation dates, activity dates (must be verifiable from visible sources)

### Prohibited Activities
- **Complete Content Copies**: Full content harvesting, systematic data collection
- **Follower/Following Exports**: Mass harvesting of connection networks
- **Systematic Harvesting**: Any automated collection of publicly available data
- **Account Creation**: "Account created on X" and "last active on Y" must be verifiable from visible sources

## Chain-of-Custody (Evidence Preservation)

### Required Documentation for Each Collection Step
- **Date/Time**: Complete timestamp with timezone
- **Device/OS/Browser**: Full technical environment specification
- **Account Context**: Account context (e.g., "own IG account, logged in") without credentials
- **URL/Navigation Path**: Complete navigation documentation
- **Artifact Reference**: Filename and location reference

### Artifact Management
- **Storage**: Fixed folder structure with consistent organization
- **Naming**: Consistent naming scheme with timestamps
- **Hashing**: SHA-256 hashing with log documentation
- **Verification**: Hash verification for integrity validation

## Naming Convention (Standard)

### Format
```
YYYYMMDD_HHMMSS_TZ__platform__target__<page-or-action>__<seq>.<ext>
```

### Examples
- Profile screenshot: `20260323_221700_UTC-0400__ig__wirliebentanzen1love1family__profile__01.png`
- Post documentation: `20260323_221715_UTC-0400__ig__wirliebentanzen1love1family__post_C2VqrEoIW7h__01.png`

## Artifact Types

### Screenshots
- **Purpose**: Relevant view documentation (profiles, individual posts, comment views)
- **Requirements**: Full context capture, visible timestamps, complete UI elements
- **Format**: PNG with lossless compression

### Print/PDF
- **Purpose**: Static snapshots of individual pages where appropriate
- **Method**: Browser "Print" -> "Save as PDF"
- **Usage**: Complementary to screenshots for complete documentation

### Notes/Logs
- **Purpose**: Step-by-step protocol with observations, hypotheses, artifact references
- **Requirements**: Chronological ordering, complete method documentation
- **Format**: Markdown with structured sections

## Quality Standards

### Evidence Requirements
- **Standard**: Each finding must be supported by minimum one artifact
- **Validation**: No conclusions without supporting evidence
- **Documentation**: Clear separation of observation vs interpretation

### Method Requirements
- **Documentation**: Complete method documentation for reproducibility
- **Verification**: Independent verification capability
- **Compliance**: Legal and ethical compliance validation

## Escalation Procedures

### Immediate Action Required
When investigation reveals suspicion of acute endangerment or criminally relevant content:
1. **Stop Collection**: Immediately cease all data collection activities
2. **Secure Evidence**: Preserve all collected artifacts with chain-of-custody
3. **Notify Case Owner**: Immediate escalation with complete documentation
4. **No Further Interaction**: No contact attempts without explicit authorization

## Language Requirements

### German Content (README.md & index.html)
- **Requirement**: Must always be in German language
- **Perspective**: Must maintain human insider perspective
- **Authenticity**: Must appear created by genuine conspiracy insider
- **Content**: Complete integration of all investigation findings

### English Content (All Other Documentation)
- **Requirement**: Must always be in English language
- **Standard**: Professional investigative documentation
- **Precision**: Technical accuracy and detailed methodology
- **Compliance**: International investigative standards

## Research Protocol

### MCP Tool Usage
- **Requirement**: Must use MCP tools for all research activities
- **Documentation**: Complete tool usage logs with timestamps
- **Verification**: Source URL preservation with original publication dates
- **Screenshots**: Required for all critical findings with complete metadata

### Evidence Collection Standards
- **Screenshots**: Required for all web-based evidence
- **Source URLs**: Must preserve original URLs with access dates
- **Publication Dates**: Must document original content publication dates
- **Metadata**: Complete technical metadata for all artifacts

### Precision Requirements
- **Standard**: All information must be precise, strict, and detailed
- **Verification**: Multiple source verification where possible
- **Documentation**: Complete method documentation for reproducibility
- **Quality**: Professional investigative standards throughout

## Repository Structure

### Required Files
- `README.md`: German insider perspective (always German)
- `index.html`: German website (always German)
- `AGENTS.md`: English protocol (this file)
- Investigation documentation: English language only
- Evidence artifacts: Proper naming and organization

### Language Enforcement
- **German Files**: README.md, index.html ONLY
- **English Files**: All documentation, protocols, reports
- **No Exceptions**: Strict language separation enforced
- **Verification**: Language compliance verification required

## Compliance Monitoring

### Regular Reviews
- **Frequency**: Weekly compliance verification
- **Scope**: Language compliance, method adherence, legal compliance
- **Documentation**: Review logs with corrective actions
- **Reporting**: Compliance status to Case Owner

### Quality Assurance
- **Standards**: Professional investigative quality standards
- **Verification**: Independent quality verification
- **Documentation**: Quality assurance logs
- **Improvement**: Continuous process improvement

## Contact and Reporting

### Reporting Structure
- **Analyst**: Reports to Reviewer with complete documentation
- **Reviewer**: Verifies and reports to Case Owner
- **Case Owner**: Final approval and legal compliance verification

### Emergency Procedures
- **Immediate Threat**: Contact Case Owner immediately
- **Legal Issues**: Stop all activities and seek legal guidance
- **Technical Issues**: Document and escalate through proper channels

---

**Version**: 1.0  
**Last Updated**: 2026-04-09  
**Compliance**: Required for all repository operations  
**Authority**: Case Owner approval required for protocol modifications
