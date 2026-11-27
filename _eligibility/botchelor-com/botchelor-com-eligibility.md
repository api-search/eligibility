---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - FR
    - IT
    - DE
    - AU
    - BR
    served: []
    text: 'After Dark, when it opens, won''t be offered where the law asks for an age check we don''t offer: ... France, Italy, Germany, Australia and Brazil , and any country where adult content like it is against the law'
  entity_types:
  - text: Botchelor is for adults (18+). By using it you confirm that you are at least 18
    type: individual
  minimum_age:
    text: Botchelor is for adults (18+).
    value: '18'
  restricted_uses:
  - summary: Fictional adults only
    text: Every character is 18 or older and reads as an adult.
  - summary: No real people
    text: No celebrities, public figures or anyone you know, by name or by likeness.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By using it you confirm that you are at least 18, and old enough to agree to these terms where you live
excluded_countries:
- FR
- IT
- DE
- AU
- BR
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Botchelor
provenance_date: '2026-11-09'
provider_name: Botchelor
provider_slug: botchelor-com
slug: botchelor-com-eligibility
source_date: '2026-11-09'
source_filename: botchelor-com-eligibility.yml
source_heading: Eligibility
source_page: https://botchelor.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Botchelor\naid: botchelor-com\nurl: https://botchelor.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - FR\n  - IT\n  - DE\n  - AU\n  - BR\n  text: 'After Dark, when it opens, won''t be offered where the law asks for an age check we don''t offer: ... France,\n    Italy, Germany, Australia and Brazil , and any country where adult content like it is against the law'\nentity_types:\n- type: individual\n  text: Botchelor is for adults (18+). By using it you confirm that you are at least 18\nrestricted_uses:\n- summary: Fictional adults only\n  text: Every character is 18 or older and\
  \ reads as an adult.\n- summary: No real people\n  text: No celebrities, public figures or anyone you know, by name or by likeness.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By using it you confirm that you are at least 18, and old enough to agree to these terms where you live\nminimum_age:\n  value: '18'\n  text: Botchelor is for adults (18+).\n"
source_yaml_url: https://artifacts.apis.io/botchelor-com/eligibility/botchelor-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Botchelor's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
