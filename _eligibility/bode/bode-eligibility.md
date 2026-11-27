---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Unlawful, harmful or abusive activity
    text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'
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
name: Bode
provenance_date: '2026-11-09'
provider_name: Bode
provider_slug: bode
slug: bode-eligibility
source_date: '2026-11-09'
source_filename: bode-eligibility.yml
source_heading: Eligibility
source_page: https://bode.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bode\naid: bode\nurl: https://bode.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, harmful or abusive activity\n  text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/bode/eligibility/bode-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Bode's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fashion
- E-Commerce
- Clothing
- Accessories
- Home Goods
---
