---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You represent and warrant to us that you are employed by an institution which:'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful material
    text: use the 9fin Service to access, store, distribute, or transmit any material that is unlawful, harmful, threatening, defamatory, inflammatory, violent, obscene, infringing, harassing, or racially or ethnically offensive
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 9fin reserves the right to decline or accept any request to register for the 9fin Service in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 9FIN
provenance_date: '2026-11-09'
provider_name: 9FIN
provider_slug: 9fin
slug: 9fin-eligibility
source_date: '2026-11-09'
source_filename: 9fin-eligibility.yml
source_heading: Eligibility
source_page: https://www.9fin.com/terms/terms-of-use/v1.0
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 9FIN\naid: 9fin\nurl: https://www.9fin.com/terms/terms-of-use/v1.0\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'You represent and warrant to us that you are employed by an institution which:'\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: use the 9fin Service to access, store, distribute, or transmit any material that is unlawful, harmful, threatening,\n    defamatory, inflammatory, violent, obscene, infringing, harassing, or racially or ethnically offensive\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: 9fin reserves the right to decline or accept any request to register for the 9fin Service in its sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/9fin/eligibility/9fin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from 9FIN's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fixed Income
- Credit Intelligence
- Leveraged Finance
- Private Credit
- Debt Capital Markets
- Market Data
- Artificial Intelligence
---
