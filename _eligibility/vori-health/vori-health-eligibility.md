---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Accessing this Site or use of any of its content or services from locations where such access or use of its content or services is illegal is prohibited.
  entity_types:
  - text: you are at least eighteen (18) years of age and are able to legally bind the Minor
    type: individual
  minimum_age:
    text: Our service is intended for use by individuals who are at least thirteen (13) years of age.
    value: '13'
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
name: Vori Health
provenance_date: '2026-11-10'
provider_name: Vori Health
provider_slug: vori-health
slug: vori-health-eligibility
source_date: '2026-11-10'
source_filename: vori-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.vorihealth.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vori Health\naid: vori-health\nurl: https://www.vorihealth.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Accessing this Site or use of any of its content or services from locations where such access or use of\n    its content or services is illegal is prohibited.\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age and are able to legally bind the Minor\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our service is intended for use\
  \ by individuals who are at least thirteen (13) years of age.\n"
source_yaml_url: https://artifacts.apis.io/vori-health/eligibility/vori-health-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Vori Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Musculoskeletal
- Telehealth
- Virtual Care
- Physical Therapy
- Orthopedics
- Employer Benefits
- Value-Based Care
- United States
---
