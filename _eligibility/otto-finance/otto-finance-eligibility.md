---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer user, we are not liable for any loss or damage to your business, but we aim to repair or provide a refund for any damage caused by our faulty digital content.
    type: individual
  - text: If you are a business user, we exclude all implied conditions, warranties, representations or other terms that may apply to our site or any content on it
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing uploads
    text: you undertake not to post to or send via this website any materials that are or could reasonably be construed as
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
name: Otto Finance
provenance_date: '2026-11-10'
provider_name: Otto Finance
provider_slug: otto-finance
slug: otto-finance-eligibility
source_date: '2026-11-10'
source_filename: otto-finance-eligibility.yml
source_heading: Eligibility
source_page: https://ottofinance.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Otto Finance\naid: otto-finance\nurl: https://ottofinance.io/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer user, we are not liable for any loss or damage to your business, but we aim to repair\n    or provide a refund for any damage caused by our faulty digital content.\n- type: business\n  text: If you are a business user, we exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site or any content on it\nrestricted_uses:\n- summary: Unlawful or infringing\
  \ uploads\n  text: you undertake not to post to or send via this website any materials that are or could reasonably be construed\n    as\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/otto-finance/eligibility/otto-finance-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Otto Finance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Wealth Management
- Automation
- Artificial Intelligence
---
