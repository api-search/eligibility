---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 만 14세 이상이 아닌 경우
    value: '14'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 이용계약은 이용자의 약관동의와 이용신청에 대한 회사의 승낙으로 성립합니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PUBLY
provenance_date: '2026-11-10'
provider_name: PUBLY
provider_slug: publy
slug: publy-eligibility
source_date: '2026-11-10'
source_filename: publy-eligibility.yml
source_heading: Eligibility
source_page: https://publy.co/content/755
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PUBLY\naid: publy\nurl: https://publy.co/content/755\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 이용계약은 이용자의 약관동의와 이용신청에 대한 회사의 승낙으로 성립합니다.\nminimum_age:\n  value: '14'\n  text: 만 14세 이상이 아닌 경우\n"
source_yaml_url: https://artifacts.apis.io/publy/eligibility/publy-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from PUBLY's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Content
- Media
- Careers
- Membership
- Subscription
- Newsletters
- Professional Development
- South Korea
---
