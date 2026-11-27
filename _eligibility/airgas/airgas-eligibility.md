---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Site, and any information contained on the Site, solely for legitimate business purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: The United States Export Control laws prohibit the export of certain technical data and software to certain territories.
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
name: Airgas
provenance_date: '2026-11-09'
provider_name: Airgas
provider_slug: airgas
slug: airgas-eligibility
source_date: '2026-11-09'
source_filename: airgas-eligibility.yml
source_heading: Eligibility
source_page: https://www.airgas.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airgas\naid: airgas\nurl: https://www.airgas.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may use the Site, and any information contained on the Site, solely for legitimate business purposes.\nrestricted_uses:\n- summary: Export control restrictions\n  text: The United States Export Control laws prohibit the export of certain technical data and software to certain\n    territories.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airgas/eligibility/airgas-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Airgas's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 500
- Industrial Gases
- Welding
- Safety
- B2B
- Supply Chain
- Manufacturing
- Healthcare
---
