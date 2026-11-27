---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Terms are an agreement between you (“ You ” or the “ User ”) and Bannerflow.
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
name: Bannerflow
provenance_date: '2026-11-09'
provider_name: Bannerflow
provider_slug: bannerflow
slug: bannerflow-eligibility
source_date: '2026-11-09'
source_filename: bannerflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.bannerflow.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bannerflow\naid: bannerflow\nurl: https://www.bannerflow.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Terms are an agreement between you (“ You ” or the “ User ”) and Bannerflow.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bannerflow/eligibility/bannerflow-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Bannerflow's own page on 2026-11-09.
synthetic: false
tags:
- Creative Automation
- Ad Production
- Dynamic Creative Optimization
- Localization
- Real‑time Campaign Management
- Marketing Technology
---
