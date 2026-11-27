---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Persons eligible for membership are natural persons who: - have the legal authority to agree to the programme terms and conditions'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purpose of stay
    text: (iv) the purpose or reason for the stay is unlawful
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To verify the guest's identity, Limehome is entitled, within the legal framework, to request a valid identification document
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Limehome
provenance_date: '2026-11-09'
provider_name: Limehome
provider_slug: limehome
slug: limehome-eligibility
source_date: '2026-11-09'
source_filename: limehome-eligibility.yml
source_heading: Eligibility
source_page: https://www.limehome.com/en/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Limehome\naid: limehome\nurl: https://www.limehome.com/en/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Persons eligible for membership are natural persons who: - have the legal authority to agree to the programme\n    terms and conditions'\nrestricted_uses:\n- summary: Unlawful purpose of stay\n  text: (iv) the purpose or reason for the stay is unlawful\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To verify the guest's identity, Limehome is entitled, within the legal framework,\
  \ to request a valid identification\n    document\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/limehome/eligibility/limehome-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Limehome's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Hospitality
- Travel
- Real Estate
- PropTech
- Short-Term Rental
- Aparthotel
- Germany
- Europe
---
