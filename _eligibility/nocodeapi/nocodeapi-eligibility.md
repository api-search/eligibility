---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will not use the Service in embargoed countries
  entity_types:
  - text: “You” or “Customer” means the individual or entity using our Service
    type: individual
  - text: “You” or “Customer” means the individual or entity using our Service
    type: business
  minimum_age:
    text: You must be at least 18 years old or have parental consent to use the Service
    value: '18'
  restricted_uses:
  - summary: Cryptocurrency mining
    text: Use the Service for cryptocurrency mining
  - summary: Spam, harassment or harm
    text: Use the Service to spam, harass, or harm others
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate, complete, and current information when registering
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NoCodeAPI Pte. Ltd.
provenance_date: '2026-11-10'
provider_name: NoCodeAPI Pte. Ltd.
provider_slug: nocodeapi
slug: nocodeapi-eligibility
source_date: '2026-11-10'
source_filename: nocodeapi-eligibility.yml
source_heading: Eligibility
source_page: https://nocodeapi.com/terms-of-use-2/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NoCodeAPI Pte. Ltd.\naid: nocodeapi\nurl: https://nocodeapi.com/terms-of-use-2/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You will not use the Service in embargoed countries\nentity_types:\n- type: individual\n  text: “You” or “Customer” means the individual or entity using our Service\n- type: business\n  text: “You” or “Customer” means the individual or entity using our Service\nrestricted_uses:\n- summary: Cryptocurrency mining\n  text: Use the Service for cryptocurrency mining\n- summary: Spam, harassment or harm\n  text: Use the Service to spam, harass, or harm others\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate, complete, and current information when registering\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or have parental consent to use the Service\n"
source_yaml_url: https://artifacts.apis.io/nocodeapi/eligibility/nocodeapi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from NoCodeAPI Pte. Ltd.'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Integration
- No-Code
- Automation
---
