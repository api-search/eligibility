---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for personal or internal business purposes
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Website.
    value: '18'
  restricted_uses:
  - summary: Automated bots or scrapers
    text: Use automated tools (bots, scrapers) without our permission
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Novee Security
provenance_date: '2026-11-10'
provider_name: Novee Security
provider_slug: novee-security
slug: novee-security-eligibility
source_date: '2026-11-10'
source_filename: novee-security-eligibility.yml
source_heading: Eligibility
source_page: https://novee.security/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Novee Security\naid: novee-security\nurl: https://novee.security/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for personal or internal business purposes\nrestricted_uses:\n- summary: Automated bots or scrapers\n  text: Use automated tools (bots, scrapers) without our permission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/novee-security/eligibility/novee-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Novee Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Penetration Testing
- Artificial Intelligence
- Application Security
- DAST
- Red Teaming
- Bug Bounty
- Compliance
- Vulnerability Management
---
