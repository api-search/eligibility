---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service in violation of US export control or sanctions laws.
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or deceptive purposes
    text: or for any unlawful, deceptive or fraudulent purpose
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
name: Ad Radar
provenance_date: '2026-11-09'
provider_name: Ad Radar
provider_slug: ad-radar-dev
slug: ad-radar-dev-eligibility
source_date: '2026-11-09'
source_filename: ad-radar-dev-eligibility.yml
source_heading: Eligibility
source_page: https://ad-radar.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ad Radar\naid: ad-radar-dev\nurl: https://ad-radar.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service in violation of US export control or sanctions laws.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or deceptive purposes\n  text: or for any unlawful, deceptive or fraudulent purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/ad-radar-dev/eligibility/ad-radar-dev-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ad Radar's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Marketing
- Artificial Intelligence
- Competitive Intelligence
- Social Media
---
