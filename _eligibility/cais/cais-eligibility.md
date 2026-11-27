---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended to be used only by users who are residents of the United States.
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
name: CAIS
provenance_date: '2026-11-09'
provider_name: CAIS
provider_slug: cais
slug: cais-eligibility
source_date: '2026-11-09'
source_filename: cais-eligibility.yml
source_heading: Eligibility
source_page: https://www.caisgroup.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CAIS\naid: cais\nurl: https://www.caisgroup.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended to be used only by users who are residents of the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cais/eligibility/cais-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from CAIS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Alternative Investments
- Wealth Management
- Financial Services
- Fintech
- Private Markets
- Asset Management
- Structured Products
- Investment Platform
- Artificial Intelligence
---
