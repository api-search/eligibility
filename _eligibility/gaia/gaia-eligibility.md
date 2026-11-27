---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are provided for use in the United States. If you access the Services from outside the United States, you do so at your own risk
  entity_types:
  - text: Our Services are intended for use by you only if you are 21 years of age or over.
    type: individual
  minimum_age:
    text: You are aged 21 or over.
    value: '21'
  restricted_uses:
  - summary: Commercial use
    text: You may not access or use for any commercial purposes any part of the Services or Content.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A number of our Services are subject to additional requirements, such as credit eligibility.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gaia
provenance_date: '2026-11-09'
provider_name: Gaia
provider_slug: gaia
slug: gaia-eligibility
source_date: '2026-11-09'
source_filename: gaia-eligibility.yml
source_heading: Eligibility
source_page: https://gaiafamily.com/en-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gaia\naid: gaia\nurl: https://gaiafamily.com/en-us/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are provided for use in the United States. If you access the Services from outside the United\n    States, you do so at your own risk\nentity_types:\n- type: individual\n  text: Our Services are intended for use by you only if you are 21 years of age or over.\nrestricted_uses:\n- summary: Commercial use\n  text: You may not access or use for any commercial purposes any part of the Services or Content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: A number of our Services are subject to additional requirements, such as credit eligibility.\nminimum_age:\n  value: '21'\n  text: You are aged 21 or over.\n"
source_yaml_url: https://artifacts.apis.io/gaia/eligibility/gaia-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Gaia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Fertility
- IVF
- Fintech
- Family Planning
- Reproductive Health
- Femtech
- Insurance
---
