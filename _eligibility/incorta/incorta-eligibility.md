---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Interactive Areas are available for individuals aged 13 years or older.
    value: '13'
  restricted_uses:
  - summary: Prohibited User Content and conduct
    text: you agree that you will not upload, post or otherwise transmit any User Content that (a) violates or infringes in any way upon the rights of others
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
name: Incorta
provenance_date: '2026-11-09'
provider_name: Incorta
provider_slug: incorta
slug: incorta-eligibility
source_date: '2026-11-09'
source_filename: incorta-eligibility.yml
source_heading: Eligibility
source_page: https://www.incorta.com/legal-pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Incorta\naid: incorta\nurl: https://www.incorta.com/legal-pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited User Content and conduct\n  text: you agree that you will not upload, post or otherwise transmit any User Content that (a) violates or infringes\n    in any way upon the rights of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Interactive Areas are available for individuals aged 13 years or older.\n"
source_yaml_url: https://artifacts.apis.io/incorta/eligibility/incorta-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Incorta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Analytics
- Business Intelligence
- Data Platform
- Data Analytics
- Data Integration
- Dashboards
---
