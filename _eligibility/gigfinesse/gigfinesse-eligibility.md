---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  minimum_age:
    text: Our Website or Services are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No commercial exploitation
    text: License, sell, rent, lease, transfer, assign or otherwise commercially exploit the Website or Services
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
name: GigFinesse
provenance_date: '2026-11-09'
provider_name: GigFinesse
provider_slug: gigfinesse
slug: gigfinesse-eligibility
source_date: '2026-11-09'
source_filename: gigfinesse-eligibility.yml
source_heading: Eligibility
source_page: https://www.gigfinesse.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GigFinesse\naid: gigfinesse\nurl: https://www.gigfinesse.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: No commercial exploitation\n  text: License, sell, rent, lease, transfer, assign or otherwise commercially exploit the Website or Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Website or Services are offered and available to users who are 18 years of age\
  \ or older.\n"
source_yaml_url: https://artifacts.apis.io/gigfinesse/eligibility/gigfinesse-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from GigFinesse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vertical Software
- Live Entertainment
- Talent Booking
- Hospitality
- Music
- Marketplace
---
