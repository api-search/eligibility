---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years of age
    type: individual
  - text: Operate a legitimate business (for merchant accounts)
    type: business
  minimum_age:
    text: Be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal purpose
    text: Use the Service for any illegal purpose
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Credit terms are subject to approval and credit assessment
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dagangan
provenance_date: '2026-11-09'
provider_name: Dagangan
provider_slug: dagangan
slug: dagangan-eligibility
source_date: '2026-11-09'
source_filename: dagangan-eligibility.yml
source_heading: Eligibility
source_page: https://dagangan.com/terms.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dagangan\naid: dagangan\nurl: https://dagangan.com/terms.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years of age\n- type: business\n  text: Operate a legitimate business (for merchant accounts)\nrestricted_uses:\n- summary: Illegal purpose\n  text: Use the Service for any illegal purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Credit terms are subject to approval and credit assessment\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/dagangan/eligibility/dagangan-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Dagangan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Wholesale
- Logistics
- Retail
- Supply Chain
- Rural Commerce
- Indonesia
---
