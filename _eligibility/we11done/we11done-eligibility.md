---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are 18 years of age or older and are at least of the legally required age as an adult in the jurisdiction in which you reside, and are otherwise capable of entering into binding contracts.
    type: individual
  - text: excluding any use in relation to any commercial, advertising, entrepreneurial or professional activity.
    type: business
  minimum_age:
    text: You are 18 years of age or older and are at least of the legally required age as an adult in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Commercial, advertising or professional use of the Site
    text: hereby excluding any use in relation to any commercial, advertising, entrepreneurial or professional activity.
  - summary: Resale of products
    text: You may not sell or resell any products you purchase or otherwise receive from us.
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
name: WE11DONE
provenance_date: '2026-11-10'
provider_name: WE11DONE
provider_slug: we11done
slug: we11done-eligibility
source_date: '2026-11-10'
source_filename: we11done-eligibility.yml
source_heading: Eligibility
source_page: https://www.we11-done.com/us/service/agreement.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WE11DONE\naid: we11done\nurl: https://www.we11-done.com/us/service/agreement.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are 18 years of age or older and are at least of the legally required age as an adult in the jurisdiction\n    in which you reside, and are otherwise capable of entering into binding contracts.\n- type: business\n  text: excluding any use in relation to any commercial, advertising, entrepreneurial or professional activity.\nrestricted_uses:\n- summary: Commercial, advertising or professional use of the\
  \ Site\n  text: hereby excluding any use in relation to any commercial, advertising, entrepreneurial or professional activity.\n- summary: Resale of products\n  text: You may not sell or resell any products you purchase or otherwise receive from us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are 18 years of age or older and are at least of the legally required age as an adult in the jurisdiction\n    in which you reside\n"
source_yaml_url: https://artifacts.apis.io/we11done/eligibility/we11done-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from WE11DONE's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Fashion
- Retail
- E-Commerce
- Streetwear
- Apparel
- South Korea
---
