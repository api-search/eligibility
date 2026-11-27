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
    text: No minors may use this site
    value: '18'
  restricted_uses:
  - summary: Personal use only; no resale
    text: By purchasing products from us, you agree not to resell such products and that such products are for your personal use and enjoyment only.
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
name: Dameproducts
provenance_date: '2026-11-09'
provider_name: Dameproducts
provider_slug: dameproducts
slug: dameproducts-eligibility
source_date: '2026-11-09'
source_filename: dameproducts-eligibility.yml
source_heading: Eligibility
source_page: https://dame.com/pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dameproducts\naid: dameproducts\nurl: https://dame.com/pages/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Personal use only; no resale\n  text: By purchasing products from us, you agree not to resell such products and that such products are for your\n    personal use and enjoyment only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: No minors may use this site\n"
source_yaml_url: https://artifacts.apis.io/dameproducts/eligibility/dameproducts-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Dameproducts's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SexTech
- Consumer Goods
- E-Commerce
- Wellness
---
