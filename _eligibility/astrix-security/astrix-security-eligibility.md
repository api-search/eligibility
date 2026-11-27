---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals above the age of 18.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals above the age of 18.
    value: '18'
  restricted_uses:
  - summary: Disrupting servers or networks
    text: (iii) disrupt servers or networks connected to the Site
  - summary: Circumventing security features
    text: (v) circumvent, disable or otherwise interfere with security-related features of the Site
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
name: Astrix Security
provenance_date: '2026-11-09'
provider_name: Astrix Security
provider_slug: astrix-security
slug: astrix-security-eligibility
source_date: '2026-11-09'
source_filename: astrix-security-eligibility.yml
source_heading: Eligibility
source_page: https://astrix.security/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astrix Security\naid: astrix-security\nurl: https://astrix.security/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals above the age of 18.\nrestricted_uses:\n- summary: Disrupting servers or networks\n  text: (iii) disrupt servers or networks connected to the Site\n- summary: Circumventing security features\n  text: (v) circumvent, disable or otherwise interfere with security-related features of the Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: The Site is only intended for individuals above the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/astrix-security/eligibility/astrix-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Astrix Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Non-Human Identity
- Identity and Access Management
- AI Agents
- Cybersecurity
---
