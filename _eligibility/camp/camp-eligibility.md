---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To create a user account on the Site, you must be in the United States of America, 13 years or older and have the power and authority to enter into these Terms.
  minimum_age:
    text: you must be in the United States of America, 13 years or older
    value: '13'
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
name: Camp
provenance_date: '2026-11-09'
provider_name: Camp
provider_slug: camp
slug: camp-eligibility
source_date: '2026-11-09'
source_filename: camp-eligibility.yml
source_heading: Eligibility
source_page: https://camp.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Camp\naid: camp\nurl: https://camp.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To create a user account on the Site, you must be in the United States of America, 13 years or older and\n    have the power and authority to enter into these Terms.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you must be in the United States of America, 13 years or older\n"
source_yaml_url: https://artifacts.apis.io/camp/eligibility/camp-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Camp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Family Entertainment
- Experiential Retail
- Kids
- E-Commerce
- Consumer
- Toys
---
