---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 大学、大学院、短期大学、高等専門学校、専修学校又は各種学校（海外の大学等を含みます。）に在籍する学生であること。
  entity_types:
  - text: 本規約は、本サービスを利用するすべての学生ユーザー（以下「ユーザー」といいます。）に適用されます。
    type: individual
  minimum_age:
    text: ユーザーが未成年である場合には、法定代理人の同意を得た上で、本サービスを利用してください。
    value: null
  restricted_uses:
  - summary: dating with unacquainted persons of opposite sex
    text: 面識のない異性との出会いを目的とした行為
  - summary: use by anti-social forces
    text: 反社会的勢力に対して直接または間接に利益を供与する行為
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社がこれを承認することによって、本サービスの利用登録をすることができます。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ABABA
provenance_date: '2026-11-09'
provider_name: ABABA
provider_slug: ababa
slug: ababa-eligibility
source_date: '2026-11-09'
source_filename: ababa-eligibility.yml
source_heading: Eligibility
source_page: https://ababa.co.jp/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ABABA\naid: ababa\nurl: https://ababa.co.jp/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 大学、大学院、短期大学、高等専門学校、専修学校又は各種学校（海外の大学等を含みます。）に在籍する学生であること。\nentity_types:\n- type: individual\n  text: 本規約は、本サービスを利用するすべての学生ユーザー（以下「ユーザー」といいます。）に適用されます。\nrestricted_uses:\n- summary: dating with unacquainted persons of opposite sex\n  text: 面識のない異性との出会いを目的とした行為\n- summary: use by anti-social forces\n  text: 反社会的勢力に対して直接または間接に利益を供与する行為\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社がこれを承認することによって、本サービスの利用登録をすることができます。\nminimum_age:\n  value: null\n\
  \  text: ユーザーが未成年である場合には、法定代理人の同意を得た上で、本サービスを利用してください。\n"
source_yaml_url: https://artifacts.apis.io/ababa/eligibility/ababa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from ABABA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Recruiting
- Talent Acquisition
- HR Technology
- Job Search
- Artificial Intelligence
- Japan
- Software-as-a-Service
---
