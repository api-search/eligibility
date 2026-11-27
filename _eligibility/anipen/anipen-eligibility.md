---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 회원 계정을 생성하는 이용자(회원가입)
    type: individual
  minimum_age:
    text: 이용자는 18세 이상이거나, 미성년이지만 성인으로서의 권한을 가지거나, 법정대리인의 동의를 받았거나, 본 약관에 규정된 조건들에 합의하여 본 약관을 준수할 수 있는 완전한 권한이 있음을 확인합니다.
    value: null
  restricted_uses:
  - summary: Access via workarounds in unsupported countries
    text: 회사가 서비스를 제공하지 않거나, 제공할 것으로 결정하지 않은 국가에서의 비정상적 또는 우회적인 방법을 통해 이용하는 경우
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 이용자가 본 약관과 개인정보처리방침 등 회사의 운영 정책에 동의 후 직접 본인의 이메일 주소(아이디) 및 비밀번호를 등록하여 회사가 승낙하는 절차이며, 필요한 경우 이메일, 휴대전화를 통한 본인인증이 추가됩니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Anipen
provenance_date: '2026-11-09'
provider_name: Anipen
provider_slug: anipen
slug: anipen-eligibility
source_date: '2026-11-09'
source_filename: anipen-eligibility.yml
source_heading: Eligibility
source_page: https://anipen.com/termsofservice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anipen\naid: anipen\nurl: https://anipen.com/termsofservice/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 회원 계정을 생성하는 이용자(회원가입)\nrestricted_uses:\n- summary: Access via workarounds in unsupported countries\n  text: 회사가 서비스를 제공하지 않거나, 제공할 것으로 결정하지 않은 국가에서의 비정상적 또는 우회적인 방법을 통해 이용하는 경우\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 이용자가 본 약관과 개인정보처리방침 등 회사의 운영 정책에 동의 후 직접 본인의 이메일 주소(아이디) 및 비밀번호를 등록하여 회사가 승낙하는 절차이며, 필요한 경우 이메일, 휴대전화를 통한\n    본인인증이 추가됩니다.\nminimum_age:\n  value: null\n  text: 이용자는 18세 이상이거나,\
  \ 미성년이지만 성인으로서의 권한을 가지거나, 법정대리인의 동의를 받았거나, 본 약관에 규정된 조건들에 합의하여 본 약관을 준수할 수 있는 완전한 권한이 있음을\n    확인합니다.\n"
source_yaml_url: https://artifacts.apis.io/anipen/eligibility/anipen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Anipen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Extended Reality
- Augmented Reality
- Artificial Intelligence
- Metaverse
---
