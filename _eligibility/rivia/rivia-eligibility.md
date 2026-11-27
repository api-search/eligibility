---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer is a Biotechnology company involved in the research, development and manufacturing of medicines for use in humans.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful content/activity
    text: The Services may not be used in any jurisdiction for unlawful, obscene, offensive or fraudulent content or activity
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
name: Rivia
provenance_date: '2026-11-10'
provider_name: Rivia
provider_slug: rivia
slug: rivia-eligibility
source_date: '2026-11-10'
source_filename: rivia-eligibility.yml
source_heading: Eligibility
source_page: https://www.rivia.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rivia\naid: rivia\nurl: https://www.rivia.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer is a Biotechnology company involved in the research, development and manufacturing of medicines\n    for use in humans.\nrestricted_uses:\n- summary: Unlawful or harmful content/activity\n  text: The Services may not be used in any jurisdiction for unlawful, obscene, offensive or fraudulent content\n    or activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rivia/eligibility/rivia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Rivia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Clinical Trials
- Healthcare
- Life Sciences
- Data Intelligence
- Pharmaceuticals
- Artificial Intelligence
- Clinical Data Management
---
