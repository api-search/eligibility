---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: The Service is intended for motoring notices issued in the United Kingdom.
  entity_types:
  - text: You must be at least 18 years old and able to enter into a binding contract.
    type: individual
  - text: Businesses and anyone with several vehicles should use a Fleet plan.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Only own or authorised notices
    text: You may only submit challenges for notices that relate to you, or that you are otherwise authorised to deal with (for example, as the registered keeper of the vehicle).
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
name: appealgo-com
provenance_date: '2026-11-09'
provider_name: appealgo-com
provider_slug: appealgo-com
slug: appealgo-com-eligibility
source_date: '2026-11-09'
source_filename: appealgo-com-eligibility.yml
source_heading: Eligibility
source_page: https://appealgo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: appealgo-com\naid: appealgo-com\nurl: https://appealgo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: The Service is intended for motoring notices issued in the United Kingdom.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding contract.\n- type: business\n  text: Businesses and anyone with several vehicles should use a Fleet plan.\nrestricted_uses:\n- summary: Only own or authorised notices\n  text: You may only submit challenges for notices that relate to you, or that you are otherwise authorised to deal\n\
  \    with (for example, as the registered keeper of the vehicle).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/appealgo-com/eligibility/appealgo-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from appealgo-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Parking
- Artificial Intelligence
- United Kingdom
- Appeals
---
