---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: You may not use the Sites or any Content for any purpose that is unlawful or prohibited by these Terms of Use
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
name: FLO
provenance_date: '2026-11-09'
provider_name: FLO
provider_slug: flo-ev
slug: flo-ev-eligibility
source_date: '2026-11-09'
source_filename: flo-ev-eligibility.yml
source_heading: Eligibility
source_page: https://www.flo.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FLO\naid: flo-ev\nurl: https://www.flo.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You may not use the Sites or any Content for any purpose that is unlawful or prohibited by these Terms of\n    Use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flo-ev/eligibility/flo-ev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from FLO's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Canada
- EV Charging
- Electricity
- Grid
- Demand Response
- Interoperability
- OCPP
- OCPI
- OpenADR
- Charge Point Operator
- Quebec
---
