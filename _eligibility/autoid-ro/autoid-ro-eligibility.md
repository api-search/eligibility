---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Client profesional / B2B – persoana juridică, PFA sau alt profesionist care achiziționează în legătură cu activitatea sa economică/profesională.
    type: business
  - text: Consumator – persoana fizică ce acționează în scopuri din afara activității sale comerciale, industriale, artizanale sau profesionale.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: AutoID
provenance_date: '2026-11-09'
provider_name: AutoID
provider_slug: autoid-ro
slug: autoid-ro-eligibility
source_date: '2026-11-09'
source_filename: autoid-ro-eligibility.yml
source_heading: Eligibility
source_page: https://www.autoid.ro/termeni-si-conditii/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AutoID\naid: autoid-ro\nurl: https://www.autoid.ro/termeni-si-conditii/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Client profesional / B2B – persoana juridică, PFA sau alt profesionist care achiziționează în legătură cu\n    activitatea sa economică/profesională.\n- type: individual\n  text: Consumator – persoana fizică ce acționează în scopuri din afara activității sale comerciale, industriale,\n    artizanale sau profesionale.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/autoid-ro/eligibility/autoid-ro-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from AutoID's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Hardware
- RFID
- Barcodes
- Automation
---
