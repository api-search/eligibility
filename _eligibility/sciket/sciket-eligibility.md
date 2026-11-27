---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 您或您代表之學校、公司、政府單位、企業或法人（以下統稱「機構」）成為勢得科研股份有限公司之會員
    type: other
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 勢得科研股份有限公司保留是否接受您的訂單的權利
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sciket
provenance_date: '2026-11-10'
provider_name: Sciket
provider_slug: sciket
slug: sciket-eligibility
source_date: '2026-11-10'
source_filename: sciket-eligibility.yml
source_heading: Eligibility
source_page: https://www.sciket.com/purchase
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sciket\naid: sciket\nurl: https://www.sciket.com/purchase\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: 您或您代表之學校、公司、政府單位、企業或法人（以下統稱「機構」）成為勢得科研股份有限公司之會員\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 勢得科研股份有限公司保留是否接受您的訂單的權利\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sciket/eligibility/sciket-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Sciket's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Scientific Research
- Laboratory Supplies
- Procurement
- Taiwan
- B2B
---
