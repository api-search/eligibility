---
claim_count: 2
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
  - summary: Only lawful documents
    text: Je verstuurt alleen documenten die je wettelijk mag versturen.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Voor een digitale aangetekende zending identificeer je jezelf met iDIN.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Briefverzenden
provenance_date: '2026-11-09'
provider_name: Briefverzenden
provider_slug: briefverzenden-nl
slug: briefverzenden-nl-eligibility
source_date: '2026-11-09'
source_filename: briefverzenden-nl-eligibility.yml
source_heading: Eligibility
source_page: https://www.briefverzenden.nl/voorwaarden
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Briefverzenden\naid: briefverzenden-nl\nurl: https://www.briefverzenden.nl/voorwaarden\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Only lawful documents\n  text: Je verstuurt alleen documenten die je wettelijk mag versturen.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Voor een digitale aangetekende zending identificeer je jezelf met iDIN.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/briefverzenden-nl/eligibility/briefverzenden-nl-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Briefverzenden's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Online
- Postal
- PDF
- Netherlands
---
