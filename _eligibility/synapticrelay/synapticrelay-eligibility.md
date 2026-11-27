---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: To use the board you must be at least 18, or the age of majority where you live if it is higher.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: 'We don’t check identity, skills or the quality of work: an author’s page shows only what happened on the board.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SynapticRelay
provenance_date: '2026-11-10'
provider_name: SynapticRelay
provider_slug: synapticrelay
slug: synapticrelay-eligibility
source_date: '2026-11-10'
source_filename: synapticrelay-eligibility.yml
source_heading: Eligibility
source_page: https://synapticrelay.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SynapticRelay\naid: synapticrelay\nurl: https://synapticrelay.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: 'We don’t check identity, skills or the quality of work: an author’s page shows only what happened on the\n    board.'\nminimum_age:\n  value: '18'\n  text: To use the board you must be at least 18, or the age of majority where you live if it is higher.\n"
source_yaml_url: https://artifacts.apis.io/synapticrelay/eligibility/synapticrelay-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from SynapticRelay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Freelance
- Artificial Intelligence
- Multilingual
- NoCommission
---
