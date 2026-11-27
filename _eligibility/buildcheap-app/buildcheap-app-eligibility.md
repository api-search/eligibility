---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old (or the minimum age of digital consent in your country) to use the Service.
    type: individual
  - text: If you use BuildCheap on behalf of an organization, you confirm you are authorized to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old (or the minimum age of digital consent in your country) to use the Service.
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful apps
    text: You must not use BuildCheap to build or distribute anything unlawful, infringing, malicious, or harmful.
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
name: BuildCheap
provenance_date: '2026-11-09'
provider_name: BuildCheap
provider_slug: buildcheap-app
slug: buildcheap-app-eligibility
source_date: '2026-11-09'
source_filename: buildcheap-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.buildcheap.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuildCheap\naid: buildcheap-app\nurl: https://www.buildcheap.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (or the minimum age of digital consent in your country) to use the Service.\n- type: business\n  text: If you use BuildCheap on behalf of an organization, you confirm you are authorized to bind that organization\n    to these Terms.\nrestricted_uses:\n- summary: Unlawful or harmful apps\n  text: You must not use BuildCheap to build or distribute anything unlawful, infringing, malicious,\
  \ or harmful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the minimum age of digital consent in your country) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/buildcheap-app/eligibility/buildcheap-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BuildCheap's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- No-Code
- Platform
- Software-as-a-Service
- Automation
---
