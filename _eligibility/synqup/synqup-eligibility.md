---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Ist der Auftraggeber Kaufmann, eine juristische Person des öffentlichen Rechts oder ein öffentlich-rechtliches Sondervermögen oder hat er in der Bundesrepublik Deutschland keinen allgemeinen Gerichtsstand, so ist Erfüllungsort und Gerichtsstand für alle Streitigkeiten aus und im Zusammenhang mit diesem Vertrag der Sitz der synQup GmbH.
    type: business
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
name: SynqUp
provenance_date: '2026-11-10'
provider_name: SynqUp
provider_slug: synqup
slug: synqup-eligibility
source_date: '2026-11-10'
source_filename: synqup-eligibility.yml
source_heading: Eligibility
source_page: https://www.synqup.com/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SynqUp\naid: synqup\nurl: https://www.synqup.com/agb/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Ist der Auftraggeber Kaufmann, eine juristische Person des öffentlichen Rechts oder ein öffentlich-rechtliches\n    Sondervermögen oder hat er in der Bundesrepublik Deutschland keinen allgemeinen Gerichtsstand, so ist Erfüllungsort\n    und Gerichtsstand für alle Streitigkeiten aus und im Zusammenhang mit diesem Vertrag der Sitz der synQup GmbH.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/synqup/eligibility/synqup-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from SynqUp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- iPaaS
- Data Integration
- Enterprise
- Software-as-a-Service
---
