---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 본 서비스는 일반 소비자용이 아니라 기업 및 조직에서의 이용을 의도하여 제공되는 경영 도구라는 점에서
    type: business
  minimum_age:
    text: 14세 미만 아동은 본 서비스 이용이 불가하며
    value: '14'
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
name: AENTS
provenance_date: '2026-11-09'
provider_name: AENTS
provider_slug: aents
slug: aents-eligibility
source_date: '2026-11-09'
source_filename: aents-eligibility.yml
source_heading: Eligibility
source_page: https://aents.co/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AENTS\naid: aents\nurl: https://aents.co/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 본 서비스는 일반 소비자용이 아니라 기업 및 조직에서의 이용을 의도하여 제공되는 경영 도구라는 점에서\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '14'\n  text: 14세 미만 아동은 본 서비스 이용이 불가하며\n"
source_yaml_url: https://artifacts.apis.io/aents/eligibility/aents-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from AENTS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Climate Tech
- Carbon Accounting
- Carbon Management
- ESG
- Sustainability
- Greenhouse Gas
- Net Zero
- Emissions Reporting
- Software-as-a-Service
- South Korea
---
