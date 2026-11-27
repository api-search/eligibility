---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself or the organization you represent.
    type: individual
  - text: have the legal authority to enter into these Terms on behalf of yourself or the organization you represent
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Our Services are currently in a pre-launch phase and access is limited to approved design partners.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: sherpa
provenance_date: '2026-11-10'
provider_name: sherpa
provider_slug: sherpa
slug: sherpa-eligibility
source_date: '2026-11-10'
source_filename: sherpa-eligibility.yml
source_heading: Eligibility
source_page: https://sherpahq.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sherpa\naid: sherpa\nurl: https://sherpahq.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself\n    or the organization you represent.\n- type: business\n  text: have the legal authority to enter into these Terms on behalf of yourself or the organization you represent\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Our Services are currently in a pre-launch phase and access\
  \ is limited to approved design partners.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/sherpa/eligibility/sherpa-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from sherpa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- External Workforce Management
- Vendor Management System
- Managed Service Providers
- AI Agents
- Contingent Labor
- Freelancer Management
- Staffing
- Procurement
- Human Resources
---
