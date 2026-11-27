---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Diese AGB gelten gegenüber Verbrauchern (§ 13 BGB)
    type: individual
  - text: und Unternehmern (§ 14 BGB).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Heating use only unless cooling agreed
    text: Die Anlage wird ausschließlich für Heizzwecke installiert, soweit im Festpreis-Angebot nicht ausdrücklich ein Kühlbetrieb vereinbart ist.
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
name: Enter
provenance_date: '2026-11-09'
provider_name: Enter
provider_slug: enter
slug: enter-eligibility
source_date: '2026-11-09'
source_filename: enter-eligibility.yml
source_heading: Eligibility
source_page: https://www.enter.de/waermepumpe-agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enter\naid: enter\nurl: https://www.enter.de/waermepumpe-agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Diese AGB gelten gegenüber Verbrauchern (§ 13 BGB)\n- type: business\n  text: und Unternehmern (§ 14 BGB).\nrestricted_uses:\n- summary: Heating use only unless cooling agreed\n  text: Die Anlage wird ausschließlich für Heizzwecke installiert, soweit im Festpreis-Angebot nicht ausdrücklich\n    ein Kühlbetrieb vereinbart ist.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enter/eligibility/enter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Enter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Cleantech
- Energy Efficiency
- Heat Pumps
- Solar
- Building Renovation
- Germany
- Consumer
---
