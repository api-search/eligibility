---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: this warranty is ONLY VALID FOR THE INDIVIDUAL ASSOCIATED WITH THE FULFILLMENT OF THE ORIGINAL ORDER, AND FOR WHOM CIONIC HAS A VALID PRESCRIPTION ON FILE.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must provide a valid prescription for the Refurbished Neural Sleeve prior to shipment.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CIONIC
provenance_date: '2026-11-09'
provider_name: CIONIC
provider_slug: cionic
slug: cionic-eligibility
source_date: '2026-11-09'
source_filename: cionic-eligibility.yml
source_heading: Eligibility
source_page: https://www.cionic.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CIONIC\naid: cionic\nurl: https://www.cionic.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: this warranty is ONLY VALID FOR THE INDIVIDUAL ASSOCIATED WITH THE FULFILLMENT OF THE ORIGINAL ORDER, AND\n    FOR WHOM CIONIC HAS A VALID PRESCRIPTION ON FILE.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must provide a valid prescription for the Refurbished Neural Sleeve prior to shipment.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cionic/eligibility/cionic-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from CIONIC's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Medical Devices
- Wearables
- Neurotechnology
- Research
- Clinical Research
- Biomechanics
- Rehabilitation
- Digital Health
---
