---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms are intended for business use (B2B). By subscribing, you represent that you are acting in a professional capacity and not as a consumer within the meaning of the French Code de la consommation.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Adsap
provenance_date: '2026-11-09'
provider_name: Adsap
provider_slug: adsap-ai
slug: adsap-ai-eligibility
source_date: '2026-11-09'
source_filename: adsap-ai-eligibility.yml
source_heading: Eligibility
source_page: https://adsap.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adsap\naid: adsap-ai\nurl: https://adsap.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms are intended for business use (B2B). By subscribing, you represent that you are acting in a\n    professional capacity and not as a consumer within the meaning of the French Code de la consommation.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adsap-ai/eligibility/adsap-ai-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Adsap's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Automation
- Artificial Intelligence
- Software-as-a-Service
- Marketing
---
