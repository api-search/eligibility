---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in any country to which the United States has embargoed goods or has designated as a “terrorist supporting” country
  entity_types:
  - text: THE SERVICES ARE AVAILABLE ONLY TO INDIVIDUALS AGED 16 YEARS OF AGE OR OLDER.
    type: individual
  minimum_age:
    text: To use our Services, you must (1) be at least 16 years of age
    value: '16'
  restricted_uses:
  - summary: Personal use only; no competition
    text: You agree to only use our Services for personal reasons and not, for example, to compete with us.
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
name: LTK
provenance_date: '2026-11-09'
provider_name: LTK
provider_slug: ltk
slug: ltk-eligibility
source_date: '2026-11-09'
source_filename: ltk-eligibility.yml
source_heading: Eligibility
source_page: https://company.shopltk.com/ltk-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LTK\naid: ltk\nurl: https://company.shopltk.com/ltk-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in any country to which the United States has embargoed\n    goods or has designated as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: THE SERVICES ARE AVAILABLE ONLY TO INDIVIDUALS AGED 16 YEARS OF AGE OR OLDER.\nrestricted_uses:\n- summary: Personal use only; no competition\n  text: You agree to only use our Services for personal reasons and not, for example, to compete with us.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: To use our Services, you must (1) be at least 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/ltk/eligibility/ltk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LTK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Creator Commerce
- Affiliates
- E-Commerce
- Influencer Marketing
- Retail
- Shopping
---
