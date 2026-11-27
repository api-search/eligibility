---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years old, or the age of majority in your jurisdiction (whichever is higher), to agree to these Terms and use our services independently.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years old, or the age of majority in your jurisdiction (whichever is higher), to agree to these Terms and use our services independently.
    value: '18'
  restricted_uses:
  - summary: Visa application for minors
    text: 'If you are submitting a visa application on behalf of a minor, you represent and warrant that: (a) you are the minor’s parent or legal guardian'
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
name: Sherpa
provenance_date: '2026-11-09'
provider_name: Sherpa
provider_slug: joinsherpa-com
slug: joinsherpa-com-eligibility
source_date: '2026-11-09'
source_filename: joinsherpa-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinsherpa.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sherpa\naid: joinsherpa-com\nurl: https://www.joinsherpa.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old, or the age of majority in your jurisdiction (whichever is\n    higher), to agree to these Terms and use our services independently.\nrestricted_uses:\n- summary: Visa application for minors\n  text: 'If you are submitting a visa application on behalf of a minor, you represent and warrant that: (a) you\n    are the minor’s parent or legal guardian'\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old, or the age of majority in your jurisdiction (whichever is\n    higher), to agree to these Terms and use our services independently.\n"
source_yaml_url: https://artifacts.apis.io/joinsherpa-com/eligibility/joinsherpa-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sherpa's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- eVisa
- Airlines
- TravelTech
---
