---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Vertragspartner können nur Unternehmer im Sinne des § 14 BGB oder Träger öffentlicher Gewalt sein.
    type: business
  - text: Vertragspartner können nur Unternehmer im Sinne des § 14 BGB oder Träger öffentlicher Gewalt sein.
    type: government
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: true
    kyc: null
    text: Auf Verlangen ist ein geeigneter Nachweis über diese Eigenschaften zu erbringen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sdui
provenance_date: '2026-11-10'
provider_name: Sdui
provider_slug: sdui
slug: sdui-eligibility
source_date: '2026-11-10'
source_filename: sdui-eligibility.yml
source_heading: Eligibility
source_page: https://sdui.de/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sdui\naid: sdui\nurl: https://sdui.de/agb/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Vertragspartner können nur Unternehmer im Sinne des § 14 BGB oder Träger öffentlicher Gewalt sein.\n- type: government\n  text: Vertragspartner können nur Unternehmer im Sinne des § 14 BGB oder Träger öffentlicher Gewalt sein.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: true\n  approval_required: null\n  text: Auf Verlangen ist ein geeigneter Nachweis über diese Eigenschaften zu erbringen.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sdui/eligibility/sdui-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Sdui's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Schools
- Communications
- Messaging
- Timetabling
- Grade Management
- Germany
- GDPR
---
