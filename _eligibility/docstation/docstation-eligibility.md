---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: as an individual provider of healthcare services
    type: individual
  - text: authorized official on behalf of a healthcare provider, payer, or clearinghouse
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use outside permitted purposes
    text: You will not use the Services for any purposes other than those described in Section 3.4.1 or Section 3.4.2.
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
name: DocStation
provenance_date: '2026-11-09'
provider_name: DocStation
provider_slug: docstation
slug: docstation-eligibility
source_date: '2026-11-09'
source_filename: docstation-eligibility.yml
source_heading: Eligibility
source_page: https://docstation.co/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DocStation\naid: docstation\nurl: https://docstation.co/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: as an individual provider of healthcare services\n- type: business\n  text: authorized official on behalf of a healthcare provider, payer, or clearinghouse\nrestricted_uses:\n- summary: No use outside permitted purposes\n  text: You will not use the Services for any purposes other than those described in Section 3.4.1 or Section 3.4.2.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/docstation/eligibility/docstation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from DocStation's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmacy
- Medical Billing
- Healthcare
- Clinical Services
- Patient Management
- Scheduling
- Insurance Claims
- HIPAA
---
