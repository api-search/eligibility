---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You warrant to us that you are of 18 years or above and are competent to enter into this agreement
    type: individual
  - text: in the event, You are entering into these Terms on behalf of any entity/company or its group, You possess the requisite authority to bind such entities, company or its groups to these Terms
    type: business
  minimum_age:
    text: You warrant to us that you are of 18 years or above
    value: '18'
  restricted_uses:
  - summary: PHI without a Business Associate Agreement
    text: (d) use the Services to transmit PHI without entering into a separate Business Associate Agreement with Us
  - summary: Sensitive personal information
    text: (c) use the Service(s), store or transmit Sensitive Personal Information
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
name: SuperOps
provenance_date: '2026-11-10'
provider_name: SuperOps
provider_slug: superops
slug: superops-eligibility
source_date: '2026-11-10'
source_filename: superops-eligibility.yml
source_heading: Eligibility
source_page: https://superops.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SuperOps\naid: superops\nurl: https://superops.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You warrant to us that you are of 18 years or above and are competent to enter into this agreement\n- type: business\n  text: in the event, You are entering into these Terms on behalf of any entity/company or its group, You possess\n    the requisite authority to bind such entities, company or its groups to these Terms\nrestricted_uses:\n- summary: PHI without a Business Associate Agreement\n  text: (d) use the Services to transmit\
  \ PHI without entering into a separate Business Associate Agreement with\n    Us\n- summary: Sensitive personal information\n  text: (c) use the Service(s), store or transmit Sensitive Personal Information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You warrant to us that you are of 18 years or above\n"
source_yaml_url: https://artifacts.apis.io/superops/eligibility/superops-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SuperOps's own page on 2026-11-10.
synthetic: false
tags:
- Company
- It Management Software
- PSA
- RMM
- MSP
- Service Desk
- Endpoint Management
- IT Documentation
- GraphQL
---
