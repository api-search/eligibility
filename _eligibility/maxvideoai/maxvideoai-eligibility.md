---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a business or organisation, you confirm that you have authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 15 years old (or the age of digital consent in your country, whichever is higher) to use the Service.
    value: '15'
  restricted_uses:
  - summary: No biometric identification or surveillance
    text: No use of outputs for biometric identification, surveillance, or deceptive practices without required permissions and disclosures.
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
name: MaxVideoAI
provenance_date: '2026-11-10'
provider_name: MaxVideoAI
provider_slug: maxvideoai
slug: maxvideoai-eligibility
source_date: '2026-11-10'
source_filename: maxvideoai-eligibility.yml
source_heading: Eligibility
source_page: https://maxvideoai.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MaxVideoAI\naid: maxvideoai\nurl: https://maxvideoai.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a business or organisation, you confirm that you have authority to bind\n    that entity.\nrestricted_uses:\n- summary: No biometric identification or surveillance\n  text: No use of outputs for biometric identification, surveillance, or deceptive practices without required permissions\n    and disclosures.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '15'\n  text: You must be at least 15 years old (or the age of digital consent in your country, whichever is higher) to\n    use the Service.\n"
source_yaml_url: https://artifacts.apis.io/maxvideoai/eligibility/maxvideoai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from MaxVideoAI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Video Generation
- Image Generation
- MCP
- Agent-Native
- Image-to-Video
- Creative Production
- Pay-as-you-go
---
