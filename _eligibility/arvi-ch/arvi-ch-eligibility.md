---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By placing an order with ARVI SA, the buyer confirms that he or she meets the minimum legal age for purchasing alcohol in the country where he or she lives.
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
name: ARVI SA
provenance_date: '2026-11-09'
provider_name: ARVI SA
provider_slug: arvi-ch
slug: arvi-ch-eligibility
source_date: '2026-11-09'
source_filename: arvi-ch-eligibility.yml
source_heading: Eligibility
source_page: https://arvi.ch/en/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ARVI SA\naid: arvi-ch\nurl: https://arvi.ch/en/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By placing an order with ARVI SA, the buyer confirms that he or she meets the minimum legal age for purchasing\n    alcohol in the country where he or she lives.\n"
source_yaml_url: https://artifacts.apis.io/arvi-ch/eligibility/arvi-ch-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from ARVI SA's own page on 2026-11-09.
synthetic: false
tags:
- Wine
- E-Commerce
- Retail
- Switzerland
- Premium
---
