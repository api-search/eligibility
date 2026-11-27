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
  - summary: Minors buying age-restricted goods
    text: 미성년자가 담배, 주류 등 청소년보호법에서 금지하는 재화 및 용역을 구매하는 경우
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 회사는 서비스 제공 및 보안 강화를 위해 전문기관을 통한 본인인증 절차를 요구할 수 있습니다.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Newneek
provenance_date: '2026-11-10'
provider_name: Newneek
provider_slug: newneek
slug: newneek-eligibility
source_date: '2026-11-10'
source_filename: newneek-eligibility.yml
source_heading: Eligibility
source_page: https://newneek.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Newneek\naid: newneek\nurl: https://newneek.co/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Minors buying age-restricted goods\n  text: 미성년자가 담배, 주류 등 청소년보호법에서 금지하는 재화 및 용역을 구매하는 경우\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 회사는 서비스 제공 및 보안 강화를 위해 전문기관을 통한 본인인증 절차를 요구할 수 있습니다.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/newneek/eligibility/newneek-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Newneek's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Newsletters
- News
- Content
- Consumer
- South Korea
---
