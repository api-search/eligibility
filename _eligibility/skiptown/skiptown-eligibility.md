---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are offered and available to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
  entity_types:
  - text: The Services are offered and available to users who are 18 years of age or older
    type: individual
  minimum_age:
    text: The Services are offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Alcohol purchases require age 21+
    text: By purchasing alcohol from the Company, you represent and warrant that you are at least twenty-one (21) years of age or older.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Company reserves the right to refuse to provide the Services to you or your pet at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Skiptown
provenance_date: '2026-11-10'
provider_name: Skiptown
provider_slug: skiptown
slug: skiptown-eligibility
source_date: '2026-11-10'
source_filename: skiptown-eligibility.yml
source_heading: Eligibility
source_page: https://skiptown.io/legal-policies/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skiptown\naid: skiptown\nurl: https://skiptown.io/legal-policies/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are offered and available to users who are 18 years of age or older and reside in the United\n    States or any of its territories or possessions.\nentity_types:\n- type: individual\n  text: The Services are offered and available to users who are 18 years of age or older\nrestricted_uses:\n- summary: Alcohol purchases require age 21+\n  text: By purchasing alcohol from the Company, you represent and warrant that you are at least twenty-one\
  \ (21)\n    years of age or older.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Company reserves the right to refuse to provide the Services to you or your pet at any time.\nminimum_age:\n  value: '18'\n  text: The Services are offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/skiptown/eligibility/skiptown-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Skiptown's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pet Care
- Dog Daycare
- Pet Services
- Consumer App
- Franchise
- Techstars
---
