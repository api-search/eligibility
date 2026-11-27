---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is controlled and operated from within the United States.
  minimum_age:
    text: You further certify that you are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Automated access or scraping
    text: Access any of the Site or the Services through any automated means or with any automated features or devices (including use of scripts or web crawlers)
  - summary: Commercial use of site
    text: You may only use the Site and Services for your non-commercial, non-exclusive, non-assignable, non-transferable and limited personal use, and for no other purposes.
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
name: LARQ
provenance_date: '2026-11-09'
provider_name: LARQ
provider_slug: larq
slug: larq-eligibility
source_date: '2026-11-09'
source_filename: larq-eligibility.yml
source_heading: Eligibility
source_page: https://www.livelarq.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LARQ\naid: larq\nurl: https://www.livelarq.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is controlled and operated from within the United States.\nentity_types: []\nrestricted_uses:\n- summary: Automated access or scraping\n  text: Access any of the Site or the Services through any automated means or with any automated features or devices\n    (including use of scripts or web crawlers)\n- summary: Commercial use of site\n  text: You may only use the Site and Services for your non-commercial, non-exclusive, non-assignable, non-transferable\n  \
  \  and limited personal use, and for no other purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You further certify that you are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/larq/eligibility/larq-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LARQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Consumer Products
- Water
- Hydration
- Filtration
- Sustainability
- Connected Devices
- E-Commerce
---
