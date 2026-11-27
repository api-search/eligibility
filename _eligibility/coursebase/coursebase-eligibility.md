---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: クライアント企業は、ID等が盗用され、又は第三者に使用されていることが判明した場合には、直ちにその旨をコースベースに通知するとともに、コースベースからの指示に従うものとする。
    type: business
  minimum_age:
    text: null
    value: null
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
name: Coursebase
provenance_date: '2026-11-09'
provider_name: Coursebase
provider_slug: coursebase
slug: coursebase-eligibility
source_date: '2026-11-09'
source_filename: coursebase-eligibility.yml
source_heading: Eligibility
source_page: https://coursebase.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coursebase\naid: coursebase\nurl: https://coursebase.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: クライアント企業は、ID等が盗用され、又は第三者に使用されていることが判明した場合には、直ちにその旨をコースベースに通知するとともに、コースベースからの指示に従うものとする。\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coursebase/eligibility/coursebase-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Coursebase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- LMS
- Corporate Training
- E-Learning
- Education
- Employee Development
- Human Resources
---
