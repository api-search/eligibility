---
api_specs:
- filename: crescendo-lab-broadcast-api-openapi.yml
  format: yaml
  label: Crescendo Lab Broadcast API
  slug: crescendo-lab-broadcast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-broadcast-api-openapi.yml
- filename: crescendo-lab-contacts-api-openapi.yml
  format: yaml
  label: Crescendo Lab Contacts API
  slug: crescendo-lab-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-contacts-api-openapi.yml
- filename: crescendo-lab-sms-api-openapi.yml
  format: yaml
  label: Crescendo Lab SMS API
  slug: crescendo-lab-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-sms-api-openapi.yml
- filename: crescendo-lab-teams-api-openapi.yml
  format: yaml
  label: Crescendo Lab Teams API
  slug: crescendo-lab-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-teams-api-openapi.yml
- filename: crescendo-lab-maac-go-api-api-openapi.yml
  format: yaml
  label: Crescendo Lab MAAC Go API
  slug: crescendo-lab-maac-go-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crescendo-lab/openapi/crescendo-lab-maac-go-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - TW
    text: 本服務提供台灣及部分國際地區之簡訊（SMS）自助發送功能
  entity_types:
  - text: 本服務之身分驗證僅受理公司或商號（含依法辦理商業登記之行號）
    type: business
  - text: 2026 年 11 月 3 日前已以個人身分完成驗證者，得依第 7 條所定條件繼續使用
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lending, financing, gambling messages
    text: 未經主管機關許可之借貸、融資、博弈相關訊息
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
name: Crescendo Lab
provenance_date: '2026-11-09'
provider_name: Crescendo Lab
provider_slug: crescendo-lab
slug: crescendo-lab-eligibility
source_date: '2026-11-09'
source_filename: crescendo-lab-eligibility.yml
source_heading: Eligibility
source_page: https://sms.cresclab.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crescendo Lab\naid: crescendo-lab\nurl: https://sms.cresclab.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - TW\n  excluded: []\n  text: 本服務提供台灣及部分國際地區之簡訊（SMS）自助發送功能\nentity_types:\n- type: business\n  text: 本服務之身分驗證僅受理公司或商號（含依法辦理商業登記之行號）\n- type: individual\n  text: 2026 年 11 月 3 日前已以個人身分完成驗證者，得依第 7 條所定條件繼續使用\nrestricted_uses:\n- summary: Lending, financing, gambling messages\n  text: 未經主管機關許可之借貸、融資、博弈相關訊息\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crescendo-lab/eligibility/crescendo-lab-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Crescendo Lab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS
- Messaging
- Marketing Automation
- Customer Engagement
- Taiwan
- Omnichannel
- MCP
---
