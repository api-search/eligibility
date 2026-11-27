---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Wellfound makes no representation that the Site and Services are appropriate or available in other locations.
  entity_types:
  - text: 'Candidates: Users that access the Site through the account of a potential employee or contractor.'
    type: individual
  - text: 'Employers: Users that access the Site through the account of a potential employer and who possess an email address with such employer.'
    type: business
  - text: If you are not a Candidate or an Employer, for example, if you are an external third-party recruiter or agency (including talent marketplaces), then you may not use the Site or the Services for any purpose.
    type: other
  minimum_age:
    text: You are at least 16 years old, and that if you are less than 18 years old, your parent or legal guardian has agreed to stand behind any agreement you enter into
    value: '16'
  restricted_uses:
  - summary: Recruiter/agency use barred
    text: If you are not a Candidate or an Employer, for example, if you are an external third-party recruiter or agency (including talent marketplaces), then you may not use the Site or the Services for any purpose.
  - summary: Solicitation limited to recruitment
    text: you will not solicit or advertise to any other User through the Services for any other purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Wellfound does not inquire into the backgrounds of its Users or attempt to verify the Content provided by its Users (although it reserves the right to conduct any background check or other screening at any time using available public sources).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wellfound
provenance_date: '2026-11-10'
provider_name: Wellfound
provider_slug: wellfound
slug: wellfound-eligibility
source_date: '2026-11-10'
source_filename: wellfound-eligibility.yml
source_heading: Eligibility
source_page: https://wellfound.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wellfound\naid: wellfound\nurl: https://wellfound.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Wellfound makes no representation that the Site and Services are appropriate or available in other locations.\nentity_types:\n- type: individual\n  text: 'Candidates: Users that access the Site through the account of a potential employee or contractor.'\n- type: business\n  text: 'Employers: Users that access the Site through the account of a potential employer and who possess an email\n    address with such employer.'\n- type: other\n  text: If you are not a Candidate or an\
  \ Employer, for example, if you are an external third-party recruiter or\n    agency (including talent marketplaces), then you may not use the Site or the Services for any purpose.\nrestricted_uses:\n- summary: Recruiter/agency use barred\n  text: If you are not a Candidate or an Employer, for example, if you are an external third-party recruiter or\n    agency (including talent marketplaces), then you may not use the Site or the Services for any purpose.\n- summary: Solicitation limited to recruitment\n  text: you will not solicit or advertise to any other User through the Services for any other purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Wellfound does not inquire into the backgrounds of its Users or attempt to verify the Content provided by\n    its Users (although it reserves the right to conduct any background check or other screening at any time using\n    available public sources).\nminimum_age:\n  value: '16'\n  text: You are at least 16\
  \ years old, and that if you are less than 18 years old, your parent or legal guardian\n    has agreed to stand behind any agreement you enter into\n"
source_yaml_url: https://artifacts.apis.io/wellfound/eligibility/wellfound-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Wellfound's own page on 2026-11-10.
synthetic: false
tags:
- Recruiting
- Hiring
- Talent
- Human Resources
- Applicant Tracking
- Job Board
- Startups
- MCP
- Agent-Native
- OAuth
- AI Sourcing
- Authentication
---
