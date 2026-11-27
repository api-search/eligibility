---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: users of the JALA App must be at least 18 years of age or older
    type: individual
  - text: means individuals, legal entities, or companies that use the JALA App, whether registered or not.
    type: business
  minimum_age:
    text: users of the JALA App must be at least 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: You shall not use the JALA App for any purpose that is unlawful, prohibited under these T&C, or deemed unreasonable.
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
name: Jala
provenance_date: '2026-11-09'
provider_name: Jala
provider_slug: jala
slug: jala-eligibility
source_date: '2026-11-09'
source_filename: jala-eligibility.yml
source_heading: Eligibility
source_page: https://jala.tech/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jala\naid: jala\nurl: https://jala.tech/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: users of the JALA App must be at least 18 years of age or older\n- type: business\n  text: means individuals, legal entities, or companies that use the JALA App, whether registered or not.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You shall not use the JALA App for any purpose that is unlawful, prohibited under these T&C, or deemed unreasonable.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: users of the JALA App must be at least 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/jala/eligibility/jala-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Jala's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Aquaculture
- Agriculture
- Shrimp Farming
- Supply Chain
- Traceability
- Indonesia
- Data Analytics
- IoT
---
