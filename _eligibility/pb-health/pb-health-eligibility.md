---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: all marketing or promotional materials found on this Site are solely directed to individuals, companies or other entities located in India
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: (i) use this Site or its Content for any commercial purpose;
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
name: PB Health
provenance_date: '2026-11-10'
provider_name: PB Health
provider_slug: pb-health
slug: pb-health-eligibility
source_date: '2026-11-10'
source_filename: pb-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.pbhealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PB Health\naid: pb-health\nurl: https://www.pbhealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: all marketing or promotional materials found on this Site are solely directed to individuals, companies\n    or other entities located in India\nentity_types: []\nrestricted_uses:\n- summary: No commercial use\n  text: (i) use this Site or its Content for any commercial purpose;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pb-health/eligibility/pb-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from PB Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health
- Telehealth
- Home Care
- Diagnostics
- Hospitals
- Consumer Health
- Insurance
- India
---
