---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - DK
    - FI
    - 'NO'
    - SE
    text: Norway T&C for trade finance products in Norway are included as part of the offer letter, or as part of the request form.
  entity_types:
  - text: Here you can find our Trade Finance terms and conditions for corporate customers.
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
name: Nordea
provenance_date: '2026-11-10'
provider_name: Nordea
provider_slug: nordea
slug: nordea-eligibility
source_date: '2026-11-10'
source_filename: nordea-eligibility.yml
source_heading: Eligibility
source_page: https://www.nordea.com/en/terms-and-conditions-trade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nordea\naid: nordea\nurl: https://www.nordea.com/en/terms-and-conditions-trade\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DK\n  - FI\n  - 'NO'\n  - SE\n  excluded: []\n  text: Norway T&C for trade finance products in Norway are included as part of the offer letter, or as part of\n    the request form.\nentity_types:\n- type: business\n  text: Here you can find our Trade Finance terms and conditions for corporate customers.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nordea/eligibility/nordea-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Nordea's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Banking
- Finance
- Nordic
---
