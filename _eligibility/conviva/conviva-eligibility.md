---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Website Service is not authorized in any jurisdiction that does not give effect to all provisions of the Terms of Use. Company makes no representation that the Content is appropriate or available for use in locations outside of California, and accessing the Website Service is prohibited from territories where such Content is illegal.
  entity_types:
  - text: The Website Service is only intended for individuals who are at least 16 years old.
    type: individual
  minimum_age:
    text: The Website Service is only intended for individuals who are at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: No commercial activity without consent
    text: Involves commercial activities and/or sales without Company’s prior written consent such as contests, sweepstakes, barter, advertising, or pyramid schemes
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
name: Conviva
provenance_date: '2026-11-09'
provider_name: Conviva
provider_slug: conviva
slug: conviva-eligibility
source_date: '2026-11-09'
source_filename: conviva-eligibility.yml
source_heading: Eligibility
source_page: https://www.conviva.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conviva\naid: conviva\nurl: https://www.conviva.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Website Service is not authorized in any jurisdiction that does not give effect to all provisions\n    of the Terms of Use. Company makes no representation that the Content is appropriate or available for use in\n    locations outside of California, and accessing the Website Service is prohibited from territories where such\n    Content is illegal.\nentity_types:\n- type: individual\n  text: The Website Service is only intended for individuals who are at least\
  \ 16 years old.\nrestricted_uses:\n- summary: No commercial activity without consent\n  text: Involves commercial activities and/or sales without Company’s prior written consent such as contests, sweepstakes,\n    barter, advertising, or pyramid schemes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Website Service is only intended for individuals who are at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/conviva/eligibility/conviva-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Conviva's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Streaming
- Video
- Observability
- Monitoring
- Media
- Quality of Experience
- Real-Time
- Telemetry
- Agents
- MCP
- Company
---
