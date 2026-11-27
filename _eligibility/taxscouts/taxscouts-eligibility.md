---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you live in Wales, Scotland or Northern Ireland, you can also bring claims against us in the courts of the country you live in.
  entity_types:
  - text: access and use any content, information and related materials that may be made available through the Services, in each case solely for your personal use
    type: individual
  - text: To the extent that you use a product or subscription for the purposes of your trade, business, craft or profession
    type: business
  minimum_age:
    text: null
    value: null
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
name: Taxscouts
provenance_date: '2026-11-10'
provider_name: Taxscouts
provider_slug: taxscouts
slug: taxscouts-eligibility
source_date: '2026-11-10'
source_filename: taxscouts-eligibility.yml
source_heading: Eligibility
source_page: https://taxfix.com/en-uk/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Taxscouts\naid: taxscouts\nurl: https://taxfix.com/en-uk/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you live in Wales, Scotland or Northern Ireland, you can also bring claims against us in the courts of\n    the country you live in.\nentity_types:\n- type: individual\n  text: access and use any content, information and related materials that may be made available through the Services,\n    in each case solely for your personal use\n- type: business\n  text: To the extent that you use a product or subscription for the purposes of your trade, business, craft\
  \ or\n    profession\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/taxscouts/eligibility/taxscouts-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from Taxscouts's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tax
- Accounting
- Fintech
- Self Assessment
- HMRC
- United Kingdom
- Personal Finance
---
