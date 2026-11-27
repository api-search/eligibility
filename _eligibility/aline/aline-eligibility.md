---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You represent and warrant that you are not: (i) located in an embargoed country or territory'
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age and you are legally able to enter into a contract.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: You shall not use or permit use of the Service for any illegal purpose or in any manner inconsistent with these Terms.
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
name: Aline
provenance_date: '2026-11-09'
provider_name: Aline
provider_slug: aline
slug: aline-eligibility
source_date: '2026-11-09'
source_filename: aline-eligibility.yml
source_heading: Eligibility
source_page: https://www.aline.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aline\naid: aline\nurl: https://www.aline.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You represent and warrant that you are not: (i) located in an embargoed country or territory'\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age and you are legally able to enter into a\n    contract.\nrestricted_uses:\n- summary: Illegal purposes\n  text: You shall not use or permit use of the Service for any illegal purpose or in any manner inconsistent with\n    these Terms.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/aline/eligibility/aline-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aline's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Legal AI
- Contract Lifecycle Management
- Contract Management
- E-Signature
- Artificial Intelligence
- Workflow Automation
---
