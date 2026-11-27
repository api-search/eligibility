---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we make no representation that materials on this Site are appropriate or available for use in locations outside the United States.
  entity_types:
  - text: You must be at least 18 years old to access this Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to access this Site.
    value: '18'
  restricted_uses:
  - summary: Not a substitute for medical advice
    text: No material on this site is intended to be a substitute for professional medical advice, diagnosis or treatment.
  - summary: No commercial use
    text: You must not access or use for any commercial purposes any part of the Website or any services or materials available through the Website.
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
name: Gameto
provenance_date: '2026-11-09'
provider_name: Gameto
provider_slug: gameto
slug: gameto-eligibility
source_date: '2026-11-09'
source_filename: gameto-eligibility.yml
source_heading: Eligibility
source_page: https://www.gametogen.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gameto\naid: gameto\nurl: https://www.gametogen.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: we make no representation that materials on this Site are appropriate or available for use in locations\n    outside the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to access this Site.\nrestricted_uses:\n- summary: Not a substitute for medical advice\n  text: No material on this site is intended to be a substitute for professional medical advice, diagnosis or treatment.\n- summary: No commercial use\n  text: You must\
  \ not access or use for any commercial purposes any part of the Website or any services or materials\n    available through the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to access this Site.\n"
source_yaml_url: https://artifacts.apis.io/gameto/eligibility/gameto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Gameto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotech Therapeutics
- Fertility
- Reproductive Health
- Women's Health
- IVF
- Stem Cells
---
