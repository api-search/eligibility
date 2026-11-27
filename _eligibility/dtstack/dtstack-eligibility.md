---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 您应当是具备完全民事权利能力和完全民事行为能力的自然人、法人或其他组织
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited conduct on the website
    text: 以任何方式违反法律法规或侵犯国家、社会公共利益
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
name: Dtstack
provenance_date: '2026-11-09'
provider_name: Dtstack
provider_slug: dtstack
slug: dtstack-eligibility
source_date: '2026-11-09'
source_filename: dtstack-eligibility.yml
source_heading: Eligibility
source_page: https://www.dtstack.com/zh-cn/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dtstack\naid: dtstack\nurl: https://www.dtstack.com/zh-cn/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: 您应当是具备完全民事权利能力和完全民事行为能力的自然人、法人或其他组织\nrestricted_uses:\n- summary: Prohibited conduct on the website\n  text: 以任何方式违反法律法规或侵犯国家、社会公共利益\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dtstack/eligibility/dtstack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dtstack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Big Data
- Artificial Intelligence
- Cloud
- Enterprise
---
