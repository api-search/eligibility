---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violation of applicable law
    text: you will not (and will not permit anyone to) engage in or attempt to engage in any activity that violates any state, national or international law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register for an account and create unique login credentials for each authorized individual user
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CYGNVS
provenance_date: '2026-11-09'
provider_name: CYGNVS
provider_slug: cygnvs
slug: cygnvs-eligibility
source_date: '2026-11-09'
source_filename: cygnvs-eligibility.yml
source_heading: Eligibility
source_page: https://cygnvs.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CYGNVS\naid: cygnvs\nurl: https://cygnvs.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violation of applicable law\n  text: you will not (and will not permit anyone to) engage in or attempt to engage in any activity that violates\n    any state, national or international law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must register for an account and create unique login credentials for each authorized individual user\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cygnvs/eligibility/cygnvs-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from CYGNVS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Incident Response
- Cyber Crisis Management
- Security
- Governance Risk Compliance
- Software-as-a-Service
- Business
---
