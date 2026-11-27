---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: AcreTrader.com is intended only for use by accredited investors who are United States ("U.S.") citizens or aliens admitted for permanent residence in the U.S., or any corporation, partnership, or other organization organized under the laws of the U.S.
  minimum_age:
    text: The Service is available only to Accredited Investors who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No access from prohibited jurisdictions
    text: Accessing the Service is prohibited from territories where the Content is prohibited.
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
name: Acretrader
provenance_date: '2026-11-09'
provider_name: Acretrader
provider_slug: acretrader
slug: acretrader-eligibility
source_date: '2026-11-09'
source_filename: acretrader-eligibility.yml
source_heading: Eligibility
source_page: https://acretrader.com/company/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acretrader\naid: acretrader\nurl: https://acretrader.com/company/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: AcreTrader.com is intended only for use by accredited investors who are United States (\"U.S.\") citizens\n    or aliens admitted for permanent residence in the U.S., or any corporation, partnership, or other organization\n    organized under the laws of the U.S.\nentity_types: []\nrestricted_uses:\n- summary: No access from prohibited jurisdictions\n  text: Accessing the Service is prohibited from territories where the Content is prohibited.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available only to Accredited Investors who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/acretrader/eligibility/acretrader-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Acretrader's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Farmland
- Investing
- Alternative Investments
- Real Estate
- Fintech
- Agriculture
- Marketplace
- Farmland Investing
- Accredited Investors
- Private Placements
- AgTech
---
