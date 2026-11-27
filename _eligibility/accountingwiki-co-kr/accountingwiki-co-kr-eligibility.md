---
claim_count: 2
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
  - summary: Commercial use and bulk copying
    text: 운영자의 사전 동의 없이 콘텐츠를 대량으로 수집(크롤링)·복제·재배포하거나 상업적 목적으로 이용할 수 없습니다.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 회원가입이나 결제 없이 무료로 제공하는 정보 제공 서비스입니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AccountingWiki
provenance_date: '2026-11-09'
provider_name: AccountingWiki
provider_slug: accountingwiki-co-kr
slug: accountingwiki-co-kr-eligibility
source_date: '2026-11-09'
source_filename: accountingwiki-co-kr-eligibility.yml
source_heading: Eligibility
source_page: https://accountingwiki.co.kr/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AccountingWiki\naid: accountingwiki-co-kr\nurl: https://accountingwiki.co.kr/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial use and bulk copying\n  text: 운영자의 사전 동의 없이 콘텐츠를 대량으로 수집(크롤링)·복제·재배포하거나 상업적 목적으로 이용할 수 없습니다.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 회원가입이나 결제 없이 무료로 제공하는 정보 제공 서비스입니다.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accountingwiki-co-kr/eligibility/accountingwiki-co-kr-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from AccountingWiki's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Finance
- Knowledge Base
- Open Source
- South Korea
---
