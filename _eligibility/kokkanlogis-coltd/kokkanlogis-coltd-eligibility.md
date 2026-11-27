---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 계약자 사망 혹은 (법인의 경우 폐업 및 청산)한 경우
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Valuable goods prohibited
    text: 현금, 수표, 어음, 주권 등의 가치를 매길 수 없거나 중대한 가치를 지니는 물품
  - summary: Illegal or hazardous goods prohibited
    text: 관련 법규에서 정하는 소지하여서는 안 되는 물품 (마약류, 독극물 등)
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 고객은 회사의 서비스를 이용함에 앞서, 신분증(주민등록증, 운전면허증), 카드 정보 등 필요한 정보를 회사에 제공하는 것에 동의합니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: KokkanLogis Co.,Ltd.
provenance_date: '2026-11-09'
provider_name: KokkanLogis Co.,Ltd.
provider_slug: kokkanlogis-coltd
slug: kokkanlogis-coltd-eligibility
source_date: '2026-11-09'
source_filename: kokkanlogis-coltd-eligibility.yml
source_heading: Eligibility
source_page: https://kokkan.co.kr/content/guide.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KokkanLogis Co.,Ltd.\naid: kokkanlogis-coltd\nurl: https://kokkan.co.kr/content/guide.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 계약자 사망 혹은 (법인의 경우 폐업 및 청산)한 경우\nrestricted_uses:\n- summary: Valuable goods prohibited\n  text: 현금, 수표, 어음, 주권 등의 가치를 매길 수 없거나 중대한 가치를 지니는 물품\n- summary: Illegal or hazardous goods prohibited\n  text: 관련 법규에서 정하는 소지하여서는 안 되는 물품 (마약류, 독극물 등)\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 고객은 회사의 서비스를 이용함에 앞서, 신분증(주민등록증, 운전면허증), 카드 정보 등 필요한 정보를 회사에 제공하는 것에 동의합니다.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kokkanlogis-coltd/eligibility/kokkanlogis-coltd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from KokkanLogis Co.,Ltd.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Self Storage
- Warehousing
- Storage As A Service
- Consumer Services
- Mobile App
- South Korea
- Franchise
---
