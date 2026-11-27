---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, deceptive or platform-prohibited ads
    text: You agree not to use the Service to create unlawful, deceptive, infringing, discriminatory, unsafe, or platform-prohibited ads or campaigns.
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
name: AdKit
provenance_date: '2026-11-09'
provider_name: AdKit
provider_slug: adkit-so
slug: adkit-so-eligibility
source_date: '2026-11-09'
source_filename: adkit-so-eligibility.yml
source_heading: Eligibility
source_page: https://adkit.so/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdKit\naid: adkit-so\nurl: https://adkit.so/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, deceptive or platform-prohibited ads\n  text: You agree not to use the Service to create unlawful, deceptive, infringing, discriminatory, unsafe, or platform-prohibited\n    ads or campaigns.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adkit-so/eligibility/adkit-so-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AdKit's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Marketing
- Artificial Intelligence
- AdTech
- Automation
---
