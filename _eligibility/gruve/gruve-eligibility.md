---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You agree that by using the Service, you are at least 18 years of age and legally able to enter into a contract.
    type: individual
  - text: If you are agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: you are at least 18 years of age and legally able to enter into a contract
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful use
    text: Is illegal or violates any federal, state, or local law or regulation
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
name: Gruve
provenance_date: '2026-11-09'
provider_name: Gruve
provider_slug: gruve
slug: gruve-eligibility
source_date: '2026-11-09'
source_filename: gruve-eligibility.yml
source_heading: Eligibility
source_page: https://gruve.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gruve\naid: gruve\nurl: https://gruve.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You agree that by using the Service, you are at least 18 years of age and legally able to enter into a contract.\n- type: business\n  text: If you are agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity’s behalf\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: Is illegal or violates any federal,\
  \ state, or local law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age and legally able to enter into a contract\n"
source_yaml_url: https://artifacts.apis.io/gruve/eligibility/gruve-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gruve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Infrastructure
- Cybersecurity
- Security Operations
- Digital Forensics
- Data and AI
- Customer Experience
- Salesforce
- Enterprise Services
- Managed Service
---
