---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This section is applicable to U.S. government Users only.
    type: government
  minimum_age:
    text: “User” means any individual aged 16 or older who Customer permits or invites to access and use the SaaS Service
    value: '16'
  restricted_uses:
  - summary: Prohibited data and high-risk activities
    text: Customer may not use the Services with Prohibited Data or for High-Risk Activities.
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
name: BuildOps
provenance_date: '2026-11-09'
provider_name: BuildOps
provider_slug: buildops
slug: buildops-eligibility
source_date: '2026-11-09'
source_filename: buildops-eligibility.yml
source_heading: Eligibility
source_page: https://buildops.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuildOps\naid: buildops\nurl: https://buildops.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: This section is applicable to U.S. government Users only.\nrestricted_uses:\n- summary: Prohibited data and high-risk activities\n  text: Customer may not use the Services with Prohibited Data or for High-Risk Activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: “User” means any individual aged 16 or older who Customer permits or invites to\
  \ access and use the SaaS\n    Service\n"
source_yaml_url: https://artifacts.apis.io/buildops/eligibility/buildops-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BuildOps's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction Software
- Field Service Management
- Contractor Management
- Commercial Services
- HVAC
- ERP Integration
- CRM
---
