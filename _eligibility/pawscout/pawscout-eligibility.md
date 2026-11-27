---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service, or any feature or part thereof, may not be available in all languages or in all countries
  entity_types:
  - text: If you are using the Service on your own behalf, you represent and warrant to us that you are at least 16 years of age
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant to us that you have the power and authority to enter into this Agreement for that organization.
    type: business
  minimum_age:
    text: you are at least 16 years of age (and that if you are 16 or older but under 18, you are under the supervision of a parent or legal guardian who agrees to be bound hereby on your behalf)
    value: '16'
  restricted_uses:
  - summary: Export restrictions
    text: the Software may not be exported or re-exported (a) into any U.S. embargoed countries, including without limitation Cuba, Iran, North Korea, Sudan or Syria
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
name: Pawscout
provenance_date: '2026-11-10'
provider_name: Pawscout
provider_slug: pawscout
slug: pawscout-eligibility
source_date: '2026-11-10'
source_filename: pawscout-eligibility.yml
source_heading: Eligibility
source_page: https://pawscout.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pawscout\naid: pawscout\nurl: https://pawscout.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service, or any feature or part thereof, may not be available in all languages or in all countries\nentity_types:\n- type: individual\n  text: If you are using the Service on your own behalf, you represent and warrant to us that you are at least 16\n    years of age\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant to us that you have\n    the power and authority to enter into this Agreement for that\
  \ organization.\nrestricted_uses:\n- summary: Export restrictions\n  text: the Software may not be exported or re-exported (a) into any U.S. embargoed countries, including without\n    limitation Cuba, Iran, North Korea, Sudan or Syria\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are at least 16 years of age (and that if you are 16 or older but under 18, you are under the supervision\n    of a parent or legal guardian who agrees to be bound hereby on your behalf)\n"
source_yaml_url: https://artifacts.apis.io/pawscout/eligibility/pawscout-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pawscout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pet Safety
- Mobile App
- GPS Tags
- Community
---
