---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A firm that prepares studies under its own name through the Service (a “partner firm”) may close its account and delete its data at any time.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you must create an account and provide accurate, complete information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClickDrag Finance
provenance_date: '2026-11-09'
provider_name: ClickDrag Finance
provider_slug: clickdrag-finance
slug: clickdrag-finance-eligibility
source_date: '2026-11-09'
source_filename: clickdrag-finance-eligibility.yml
source_heading: Eligibility
source_page: https://www.clickdragfinance.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClickDrag Finance\naid: clickdrag-finance\nurl: https://www.clickdragfinance.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: A firm that prepares studies under its own name through the Service (a “partner firm”) may close its account\n    and delete its data at any time.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you must create an account and provide accurate, complete information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clickdrag-finance/eligibility/clickdrag-finance-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from ClickDrag Finance's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Cost Segregation
- Real Estate
- Tax
---
