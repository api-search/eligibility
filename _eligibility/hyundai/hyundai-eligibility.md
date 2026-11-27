---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 회사가 서비스를 이용하는 자로 지정하는 대상으로서, 개인사업자, 주식회사 기타 사업을 운영하는 법인 등을 포함합니다.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Customer data use limited to consent scope
    text: 회원 및 사업자는 고객으로부터 동의 받은 범위(이용 목적 및 항목, 보유기간 등) 내에서만 고객의 정보를 이용하여야 하며
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
name: Hyundai
provenance_date: '2026-11-09'
provider_name: Hyundai
provider_slug: hyundai
slug: hyundai-eligibility
source_date: '2026-11-09'
source_filename: hyundai-eligibility.yml
source_heading: Eligibility
source_page: https://developers.hyundai.com/web/v1/hyundai/terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hyundai\naid: hyundai\nurl: https://developers.hyundai.com/web/v1/hyundai/terms_of_use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 회사가 서비스를 이용하는 자로 지정하는 대상으로서, 개인사업자, 주식회사 기타 사업을 운영하는 법인 등을 포함합니다.\nrestricted_uses:\n- summary: Customer data use limited to consent scope\n  text: 회원 및 사업자는 고객으로부터 동의 받은 범위(이용 목적 및 항목, 보유기간 등) 내에서만 고객의 정보를 이용하여야 하며\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hyundai/eligibility/hyundai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Hyundai's own page on 2026-11-09.
synthetic: false
tags:
- Automobiles
- Cars
- Connected Vehicles
- Mobility
- Vehicles
- Automotive
- Telematics
- Electric Vehicles
- Vehicle Data
- South Korea
---
