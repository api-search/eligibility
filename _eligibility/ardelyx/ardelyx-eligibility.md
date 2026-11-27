---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Ardelyx makes no representation that the information in the website is appropriate or available for use in other locations
  entity_types:
  - text: IF YOU ARE USING THE SERVICES ON BEHALF OF YOUR EMPLOYER, YOU REPRESENT AND WARRANT THAT YOU HAVE AUTHORITY TO BIND YOUR EMPLOYER TO THESE TERMS.
    type: business
  minimum_age:
    text: YOU ARE AT LEAST 18 YEARS OLD AND LEGALLY COMPETENT TO ENTER INTO CONTRACTS.
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: The content on the website is intended to be a general information resource and does not constitute medical advice.
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
name: Ardelyx
provenance_date: '2026-11-09'
provider_name: Ardelyx
provider_slug: ardelyx
slug: ardelyx-eligibility
source_date: '2026-11-09'
source_filename: ardelyx-eligibility.yml
source_heading: Eligibility
source_page: https://ardelyx.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ardelyx\naid: ardelyx\nurl: https://ardelyx.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Ardelyx makes no representation that the information in the website is appropriate or available for use\n    in other locations\nentity_types:\n- type: business\n  text: IF YOU ARE USING THE SERVICES ON BEHALF OF YOUR EMPLOYER, YOU REPRESENT AND WARRANT THAT YOU HAVE AUTHORITY\n    TO BIND YOUR EMPLOYER TO THESE TERMS.\nrestricted_uses:\n- summary: Not medical advice\n  text: The content on the website is intended to be a general information resource and does not\
  \ constitute medical\n    advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ARE AT LEAST 18 YEARS OLD AND LEGALLY COMPETENT TO ENTER INTO CONTRACTS.\n"
source_yaml_url: https://artifacts.apis.io/ardelyx/eligibility/ardelyx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ardelyx's own page on 2026-11-09.
synthetic: false
tags:
- Biopharma
- Healthcare
- Clinical Trials
- Kidney Disease
- Innovation
---
