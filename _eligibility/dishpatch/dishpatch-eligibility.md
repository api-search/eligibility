---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: null
  restricted_uses:
  - summary: Excessive or non-personal membership use
    text: All Memberships are intended to be used for reasonable, personal use, and we reserve the right to refuse any Product order that we determine to be excessive
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
name: Dishpatch
provenance_date: '2026-11-09'
provider_name: Dishpatch
provider_slug: dishpatch
slug: dishpatch-eligibility
source_date: '2026-11-09'
source_filename: dishpatch-eligibility.yml
source_heading: Eligibility
source_page: https://dishpatch.co.uk/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dishpatch\naid: dishpatch\nurl: https://dishpatch.co.uk/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Excessive or non-personal membership use\n  text: All Memberships are intended to be used for reasonable, personal use, and we reserve the right to refuse\n    any Product order that we determine to be excessive\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/dishpatch/eligibility/dishpatch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Dishpatch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food
- Meal Delivery
- Food Delivery
- E-Commerce
- Restaurant
- Consumer
- Retail
- United Kingdom
---
