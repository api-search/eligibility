---
api_specs:
- filename: nycu-profile-api-openapi.yml
  format: yaml
  label: National Yang Ming Chiao Tung University Profile API
  slug: nycu-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nycu/openapi/nycu-profile-api-openapi.yml
- filename: nycu-oauth-api-openapi.yml
  format: yaml
  label: National Yang Ming Chiao Tung University O Auth API
  slug: nycu-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nycu/openapi/nycu-oauth-api-openapi.yml
claim_count: 3
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
  - summary: Sensitive scopes need approval
    text: 其他進階或敏感範圍（如姓名、學籍狀態等）須經本校資訊技術服務中心審核通過，並填寫系統內申請表。
  - summary: Restricted scopes limited to in-house systems
    text: 原則上，僅限本校自行開發或維運之系統可申請接取受限授權範圍。
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 其他進階或敏感範圍（如姓名、學籍狀態等）須經本校資訊技術服務中心審核通過，並填寫系統內申請表。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: National Yang Ming Chiao Tung University
provenance_date: '2026-11-10'
provider_name: National Yang Ming Chiao Tung University
provider_slug: nycu
slug: nycu-eligibility
source_date: '2026-11-10'
source_filename: nycu-eligibility.yml
source_heading: Eligibility
source_page: https://id.nycu.edu.tw/policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: National Yang Ming Chiao Tung University\naid: nycu\nurl: https://id.nycu.edu.tw/policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive scopes need approval\n  text: 其他進階或敏感範圍（如姓名、學籍狀態等）須經本校資訊技術服務中心審核通過，並填寫系統內申請表。\n- summary: Restricted scopes limited to in-house systems\n  text: 原則上，僅限本校自行開發或維運之系統可申請接取受限授權範圍。\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 其他進階或敏感範圍（如姓名、學籍狀態等）須經本校資訊技術服務中心審核通過，並填寫系統內申請表。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nycu/eligibility/nycu-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from National Yang Ming Chiao Tung University's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Higher Education
- University
- Taiwan
- Identity
- OAuth
- Authentication
- SSO
- Research Data
- Institutional Repository
- Library
- Metadata
- OAI-PMH
- Identity Federation
---
