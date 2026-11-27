---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU MAY NOT ACCESS OR USE THE WEBSITE OR SERVICES OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    type: individual
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE WEBSITE OR SERVICES OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: No unlawful or harmful posting
    text: You are prohibited from posting or sending any unlawful, threatening, defamatory, libelous, obscene, pornographic or profane material
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
name: Lyric
provenance_date: '2026-11-10'
provider_name: Lyric
provider_slug: lyric
slug: lyric-eligibility
source_date: '2026-11-10'
source_filename: lyric-eligibility.yml
source_heading: Eligibility
source_page: https://lyric.tech/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lyric\naid: lyric\nurl: https://lyric.tech/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU MAY NOT ACCESS OR USE THE WEBSITE OR SERVICES OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\nrestricted_uses:\n- summary: No unlawful or harmful posting\n  text: You are prohibited from posting or sending any unlawful, threatening, defamatory, libelous, obscene, pornographic\n    or profane material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: YOU MAY NOT ACCESS OR USE THE WEBSITE OR SERVICES OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/lyric/eligibility/lyric-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Lyric's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Supply Chain
- Logistics
- Artificial Intelligence
- Optimization
- Forecasting
- Enterprise Software
---
