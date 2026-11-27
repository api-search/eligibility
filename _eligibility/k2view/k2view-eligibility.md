---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least 18 years of age or the age of legal maturity in your jurisdiction, whichever is higher.
    type: individual
  minimum_age:
    text: You represent that you are at least 18 years of age or the age of legal maturity in your jurisdiction, whichever is higher.
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or harmful use
    text: in any way which is unlawful, illegal, fraudulent or harmful, or in connection with any unlawful, illegal, fraudulent or harmful purpose or activity
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
name: K2view
provenance_date: '2026-11-09'
provider_name: K2view
provider_slug: k2view
slug: k2view-eligibility
source_date: '2026-11-09'
source_filename: k2view-eligibility.yml
source_heading: Eligibility
source_page: https://www.k2view.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: K2view\naid: k2view\nurl: https://www.k2view.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years of age or the age of legal maturity in your jurisdiction, whichever\n    is higher.\nrestricted_uses:\n- summary: Unlawful, fraudulent or harmful use\n  text: in any way which is unlawful, illegal, fraudulent or harmful, or in connection with any unlawful, illegal,\n    fraudulent or harmful purpose or activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years of age or the age of legal maturity in your jurisdiction, whichever\n    is higher.\n"
source_yaml_url: https://artifacts.apis.io/k2view/eligibility/k2view-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from K2view's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- Data Platform
- Artificial Intelligence
- Enterprise
---
