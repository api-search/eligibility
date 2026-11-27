---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Care providers and agents must provide valid business credentials and, where required, licensing.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Medicaid-funded placements
    text: Placements funded primarily through Medicaid or other government assistance programs may not qualify for placement fees or agent commissions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users must provide accurate information, a valid email address, and a secure password. Care providers and agents must provide valid business credentials and, where required, licensing.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Elderly Care Match
provenance_date: '2026-11-09'
provider_name: Elderly Care Match
provider_slug: elderlycarematch-com
slug: elderlycarematch-com-eligibility
source_date: '2026-11-09'
source_filename: elderlycarematch-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.elderlycarematch.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elderly Care Match\naid: elderlycarematch-com\nurl: https://www.elderlycarematch.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Care providers and agents must provide valid business credentials and, where required, licensing.\nrestricted_uses:\n- summary: Medicaid-funded placements\n  text: Placements funded primarily through Medicaid or other government assistance programs may not qualify for\n    placement fees or agent commissions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users\
  \ must provide accurate information, a valid email address, and a secure password. Care providers and\n    agents must provide valid business credentials and, where required, licensing.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/elderlycarematch-com/eligibility/elderlycarematch-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Elderly Care Match's own page on 2026-11-09.
synthetic: false
tags:
- Senior Care
- Elder Care
- Assisted Living
- Memory Care
- Adult Family Homes
- Nursing Homes
- Care Directory
- Healthcare
- Agents
- A2A
- Agent-Native
- Washington State
- United States
---
