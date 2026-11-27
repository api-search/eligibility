---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: GOOP MAKES NO REPRESENTATION THAT THE PROPERTIES IS APPROPRIATE OR AVAILABLE FOR USE AT LOCATIONS OUTSIDE OF THE UNITED STATES.
  entity_types:
  - text: In order to make purchases on the Properties, you must be 18 years of age or older
    type: individual
  minimum_age:
    text: you must be 18 years of age or over
    value: '18'
  restricted_uses:
  - summary: Personal use only for purchases
    text: Products purchased by you must be for personal use or purchased as a gift and may not be re-sold or used for commercial purposes or for any other commercial benefit.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By making an offer to purchase Products, you expressly authorize Goop to perform credit checks
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Goop
provenance_date: '2026-11-09'
provider_name: Goop
provider_slug: goop
slug: goop-eligibility
source_date: '2026-11-09'
source_filename: goop-eligibility.yml
source_heading: Eligibility
source_page: https://goop.com/web-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goop\naid: goop\nurl: https://goop.com/web-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: GOOP MAKES NO REPRESENTATION THAT THE PROPERTIES IS APPROPRIATE OR AVAILABLE FOR USE AT LOCATIONS OUTSIDE\n    OF THE UNITED STATES.\nentity_types:\n- type: individual\n  text: In order to make purchases on the Properties, you must be 18 years of age or older\nrestricted_uses:\n- summary: Personal use only for purchases\n  text: Products purchased by you must be for personal use or purchased as a gift and may not be re-sold or used\n    for commercial purposes\
  \ or for any other commercial benefit.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By making an offer to purchase Products, you expressly authorize Goop to perform credit checks\nminimum_age:\n  value: '18'\n  text: you must be 18 years of age or over\n"
source_yaml_url: https://artifacts.apis.io/goop/eligibility/goop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Goop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wellness
- Lifestyle
- Beauty
- E-Commerce
- Content
- Health
- Consumer Brand
- Retail
---
