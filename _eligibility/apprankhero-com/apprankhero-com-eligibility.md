---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a team gets the limits of the lowest plan among its members.
    type: business
  minimum_age:
    text: You must provide accurate information and be able to form a binding contract.
    value: null
  restricted_uses:
  - summary: No use violating Apple/Google terms or law
    text: Do not reverse engineer, or use the Service to violate Apple's terms, Google's terms or any law.
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
name: AppRankHero
provenance_date: '2026-11-09'
provider_name: AppRankHero
provider_slug: apprankhero-com
slug: apprankhero-com-eligibility
source_date: '2026-11-09'
source_filename: apprankhero-com-eligibility.yml
source_heading: Eligibility
source_page: https://apprankhero.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppRankHero\naid: apprankhero-com\nurl: https://apprankhero.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a team gets the limits of the lowest plan among its members.\nrestricted_uses:\n- summary: No use violating Apple/Google terms or law\n  text: Do not reverse engineer, or use the Service to violate Apple's terms, Google's terms or any law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must provide accurate information and be able to form a binding\
  \ contract.\n"
source_yaml_url: https://artifacts.apis.io/apprankhero-com/eligibility/apprankhero-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AppRankHero's own page on 2026-11-09.
synthetic: false
tags:
- ASO
- macOS
- KeywordTracking
- AI Integration
- Analytics
---
