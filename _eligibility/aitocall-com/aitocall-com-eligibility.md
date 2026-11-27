---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 만 14세 미만은 서비스를 이용할 수 없습니다.
    value: '14'
  restricted_uses:
  - summary: Impersonation, spam, harassment
    text: 타인의 신원·계정을 도용하거나 AI 비서를 이용하여 사칭·기망하는 행위
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 회원 가입은 카카오 또는 Google 로그인을 통해 진행합니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aitocall
provenance_date: '2026-11-09'
provider_name: Aitocall
provider_slug: aitocall-com
slug: aitocall-com-eligibility
source_date: '2026-11-09'
source_filename: aitocall-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.aitocall.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aitocall\naid: aitocall-com\nurl: https://www.aitocall.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Impersonation, spam, harassment\n  text: 타인의 신원·계정을 도용하거나 AI 비서를 이용하여 사칭·기망하는 행위\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 회원 가입은 카카오 또는 Google 로그인을 통해 진행합니다.\nminimum_age:\n  value: '14'\n  text: 만 14세 미만은 서비스를 이용할 수 없습니다.\n"
source_yaml_url: https://artifacts.apis.io/aitocall-com/eligibility/aitocall-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Aitocall's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Telephony
- Voice
- Communications
- Korean
---
