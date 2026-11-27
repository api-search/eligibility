---
api_specs:
- filename: tps-engage-play-api-openapi.yml
  format: yaml
  label: TPS Engage Play API
  slug: tps-engage-play-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tps-engage/openapi/tps-engage-play-api-openapi.yml
- filename: tps-engage-prefetch-api-openapi.yml
  format: yaml
  label: TPS Engage Prefetch API
  slug: tps-engage-prefetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tps-engage/openapi/tps-engage-prefetch-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform is designed primarily for business and professional advertising use
    type: business
  - text: but is also available to individuals
    type: individual
  minimum_age:
    text: You must be at least 18 (or the age of majority where you are, if higher) and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Bona fide out-of-home advertising only
    text: You may not use the Platform other than as a bona fide tool to plan, buy, and run out-of-home advertising.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: We may verify this information, including with registered authorities and our processor, and may refuse, suspend, or terminate accounts where verification fails or information is inaccurate
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TPS Engage
provenance_date: '2026-11-10'
provider_name: TPS Engage
provider_slug: tps-engage
slug: tps-engage-eligibility
source_date: '2026-11-10'
source_filename: tps-engage-eligibility.yml
source_heading: Eligibility
source_page: https://seeblindspot.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TPS Engage\naid: tps-engage\nurl: https://seeblindspot.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Platform is designed primarily for business and professional advertising use\n- type: individual\n  text: but is also available to individuals\nrestricted_uses:\n- summary: Bona fide out-of-home advertising only\n  text: You may not use the Platform other than as a bona fide tool to plan, buy, and run out-of-home advertising.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: We may\
  \ verify this information, including with registered authorities and our processor, and may refuse,\n    suspend, or terminate accounts where verification fails or information is inaccurate\nminimum_age:\n  value: '18'\n  text: You must be at least 18 (or the age of majority where you are, if higher) and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/tps-engage/eligibility/tps-engage-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from TPS Engage's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Digital Out Of Home
- Digital Billboards
- Programmatic Advertising
- Media Buying
- Out-of-Home
---
