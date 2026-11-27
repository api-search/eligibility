---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    type: individual
  - text: Applicant agrees to immediately notify the Company in writing of all changes in ownership, entity type, or company name.
    type: business
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Prohibited uses of Service
    text: 'You agree not to use Service: (a) In any way that violates any applicable national or international law or regulation.'
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
name: Elektrik App
provenance_date: '2026-11-09'
provider_name: Elektrik App
provider_slug: elektrik-app
slug: elektrik-app-eligibility
source_date: '2026-11-09'
source_filename: elektrik-app-eligibility.yml
source_heading: Eligibility
source_page: https://app.elektrikapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elektrik App\naid: elektrik-app\nurl: https://app.elektrikapp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n- type: business\n  text: Applicant agrees to immediately notify the Company in writing of all changes in ownership, entity type,\n    or company name.\nrestricted_uses:\n- summary: Prohibited uses of Service\n  text: 'You agree not to use Service: (a) In any way that violates any applicable national or international law\n\
  \    or regulation.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/elektrik-app/eligibility/elektrik-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Elektrik App's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Procurement
- Medium Voltage
- Electrical Equipment
- Energy
- Supply Chain
- EPC
- Marketplace
- EnergyTech
---
