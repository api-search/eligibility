---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You also confirm that you are not a minor and you possess the legal right and capacity to understand and agree to the Terms.
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You undertake to assure that the Site shall be used for lawful purposes only and that you shall not violate any applicable law.
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
name: Innovaccer
provenance_date: '2026-11-09'
provider_name: Innovaccer
provider_slug: innovaccer
slug: innovaccer-eligibility
source_date: '2026-11-09'
source_filename: innovaccer-eligibility.yml
source_heading: Eligibility
source_page: https://innovaccer.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Innovaccer\naid: innovaccer\nurl: https://innovaccer.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: You undertake to assure that the Site shall be used for lawful purposes only and that you shall not violate\n    any applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You also confirm that you are not a minor and you possess the legal right and capacity to understand and\n    agree to the Terms.\n"
source_yaml_url: https://artifacts.apis.io/innovaccer/eligibility/innovaccer-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Innovaccer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Data
- FHIR
- Interoperability
- Population Health
- Artificial Intelligence
- Data Platform
- Design Systems
- MCP
---
