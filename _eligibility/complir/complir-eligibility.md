---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Licensee: The legal entity or organisation entering into an Agreement with the Licensor for the use of the Platform.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Users limited to internal purposes
    text: solely for the Licensee's internal business purposes.
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
name: Complir
provenance_date: '2026-11-09'
provider_name: Complir
provider_slug: complir
slug: complir-eligibility
source_date: '2026-11-09'
source_filename: complir-eligibility.yml
source_heading: Eligibility
source_page: https://www.complir.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Complir\naid: complir\nurl: https://www.complir.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Licensee: The legal entity or organisation entering into an Agreement with the Licensor for the use of\n    the Platform.'\nrestricted_uses:\n- summary: Users limited to internal purposes\n  text: solely for the Licensee's internal business purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/complir/eligibility/complir-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Complir's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- RegTech
- Product Compliance
- Retail
- Artificial Intelligence
- Sustainability
- ESG
---
