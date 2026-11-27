---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use only by persons located in the United States.
  entity_types:
  - text: Our Services are intended for use by you only if you are 18 years of age or over.
    type: individual
  minimum_age:
    text: Our Services are intended for use by you only if you are 18 years of age or over.
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
name: Modern Fertility
provenance_date: '2026-11-10'
provider_name: Modern Fertility
provider_slug: modern-fertility
slug: modern-fertility-eligibility
source_date: '2026-11-10'
source_filename: modern-fertility-eligibility.yml
source_heading: Eligibility
source_page: https://ro.co/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modern Fertility\naid: modern-fertility\nurl: https://ro.co/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: Our Services are intended for use by you only if you are 18 years of age or over.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are intended for use by you only if you are 18 years of age or over.\n"
source_yaml_url: https://artifacts.apis.io/modern-fertility/eligibility/modern-fertility-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Modern Fertility's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Fertility
- Women's Health
- Hormone Testing
- Diagnostics
- Telehealth
- Consumer Health
---
