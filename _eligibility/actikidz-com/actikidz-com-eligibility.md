---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 家长或法定监护人可为自己和孩子注册账户；教师、私教和教育机构可注册机构账户。
    type: individual
  minimum_age:
    text: 家长账户和机构账户的持有人须已达所在省份的成年年龄。
    value: null
  restricted_uses:
  - summary: Bulk account registration or invite code abuse
    text: 批量注册账户或滥用邀请码
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
name: ActiKidz
provenance_date: '2026-11-09'
provider_name: ActiKidz
provider_slug: actikidz-com
slug: actikidz-com-eligibility
source_date: '2026-11-09'
source_filename: actikidz-com-eligibility.yml
source_heading: Eligibility
source_page: https://actikidz.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ActiKidz\naid: actikidz-com\nurl: https://actikidz.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 家长或法定监护人可为自己和孩子注册账户；教师、私教和教育机构可注册机构账户。\nrestricted_uses:\n- summary: Bulk account registration or invite code abuse\n  text: 批量注册账户或滥用邀请码\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: 家长账户和机构账户的持有人须已达所在省份的成年年龄。\n"
source_yaml_url: https://artifacts.apis.io/actikidz-com/eligibility/actikidz-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ActiKidz's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Platform
- Children
- Courses
- Activities
---
