---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Die AGB gelten auch für alle Folgegeschäfte im Rahmen einer laufenden Geschäftsverbindung mit einem Kaufmann als Nutzer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use only for contractual purposes
    text: Der Nutzer darf die Leistungen des Anbieters und die für die Leistungserbringung eingesetzten Instrumente, einschließlich der Leistungsergebnisse des Anbieters nur für die nutzungsvertraglich vereinbarten Zwecke nutzen bzw. in Anspruch nehmen und nur in dem nutzungsvertraglich vereinbarten Umfang.
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
name: Complori
provenance_date: '2026-11-09'
provider_name: Complori
provider_slug: complori
slug: complori-eligibility
source_date: '2026-11-09'
source_filename: complori-eligibility.yml
source_heading: Eligibility
source_page: https://app.complori.com/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Complori\naid: complori\nurl: https://app.complori.com/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Die AGB gelten auch für alle Folgegeschäfte im Rahmen einer laufenden Geschäftsverbindung mit einem Kaufmann\n    als Nutzer\nrestricted_uses:\n- summary: Use only for contractual purposes\n  text: Der Nutzer darf die Leistungen des Anbieters und die für die Leistungserbringung eingesetzten Instrumente,\n    einschließlich der Leistungsergebnisse des Anbieters nur für die nutzungsvertraglich vereinbarten Zwecke nutzen\n    bzw.\
  \ in Anspruch nehmen und nur in dem nutzungsvertraglich vereinbarten Umfang.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/complori/eligibility/complori-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Complori's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- E-Learning
- Coding
- Programming
- Kids
- Germany
---
