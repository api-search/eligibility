---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - KR
    text: This Agreement applies only to Inventory originating from the Republic of Korea and any other territories as may be expressly designated by Pangle in writing from time to time.
  entity_types:
  - text: If you are using the Pangle Platform on behalf of a company or organisation, then you represent and warrant that you are an authorised representative of such company or organisation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Minor-directed properties
    text: Partner shall not make available to Pangle, nor enable Pangle to collect, Sensitive Data or Personal Data relating to Minors, or Personal Data from Properties directed to or marketed at Minors
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
name: Pangle
provenance_date: '2026-11-10'
provider_name: Pangle
provider_slug: pangle
slug: pangle-eligibility
source_date: '2026-11-10'
source_filename: pangle-eligibility.yml
source_heading: Eligibility
source_page: https://www.pangleglobal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pangle\naid: pangle\nurl: https://www.pangleglobal.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - KR\n  excluded: []\n  text: This Agreement applies only to Inventory originating from the Republic of Korea and any other territories\n    as may be expressly designated by Pangle in writing from time to time.\nentity_types:\n- type: business\n  text: If you are using the Pangle Platform on behalf of a company or organisation, then you represent and warrant\n    that you are an authorised representative of such company or organisation\nrestricted_uses:\n- summary: Minor-directed properties\n  text:\
  \ Partner shall not make available to Pangle, nor enable Pangle to collect, Sensitive Data or Personal Data\n    relating to Minors, or Personal Data from Properties directed to or marketed at Minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pangle/eligibility/pangle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pangle's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Mobile
- Monetization
- TikTok
- In-App
---
