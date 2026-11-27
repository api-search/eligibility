---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To the extent the California Electronic Commerce Act of 1984 applies, California users are advised that the technology and Site are provided by Brightside Health, Inc.
  entity_types:
  - text: You may use the Services only if you are 18 years old or older, or if you are expressly authorized by a parent or legal guardian who agrees to bind both you and themself by these Terms.
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years old or older, or if you are expressly authorized by a parent or legal guardian
    value: '18'
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
name: Brightside Health
provenance_date: '2026-11-09'
provider_name: Brightside Health
provider_slug: brightside-health
slug: brightside-health-eligibility
source_date: '2026-11-09'
source_filename: brightside-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.brightside.com/tou/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brightside Health\naid: brightside-health\nurl: https://www.brightside.com/tou/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To the extent the California Electronic Commerce Act of 1984 applies, California users are advised that\n    the technology and Site are provided by Brightside Health, Inc.\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years old or older, or if you are expressly authorized by a\n    parent or legal guardian who agrees to bind both you and themself by these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years old or older, or if you are expressly authorized by a\n    parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/brightside-health/eligibility/brightside-health-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Brightside Health's own page on 2026-11-09.
synthetic: false
tags:
- Telehealth
- Mental Health
- Behavioral Health
- Psychiatry
- Therapy
- Digital Health
- Healthcare
- Medication Management
- Substance Use Disorder
- Suicide Prevention
- Health Plans
---
