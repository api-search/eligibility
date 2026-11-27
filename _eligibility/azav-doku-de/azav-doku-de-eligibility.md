---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: AZAV-Doku richtet sich ausschließlich an Unternehmer im Sinne des § 14 BGB, juristische Personen des öffentlichen Rechts und öffentlich-rechtliche Sondervermögen („Kunde“), insbesondere an Träger von Maßnahmen und selbstständige Coaches.
    type: business
  - text: Verbraucher können keinen Vertrag schließen.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only own measures
    text: Der Kunde nutzt AZAV-Doku nur für eigene Maßnahmen und nur rechtmäßig.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Der Kunde bestätigt bei der Registrierung, dass er als Unternehmer handelt.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AZAV-Doku
provenance_date: '2026-11-09'
provider_name: AZAV-Doku
provider_slug: azav-doku-de
slug: azav-doku-de-eligibility
source_date: '2026-11-09'
source_filename: azav-doku-de-eligibility.yml
source_heading: Eligibility
source_page: https://azav-doku.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AZAV-Doku\naid: azav-doku-de\nurl: https://azav-doku.de/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: AZAV-Doku richtet sich ausschließlich an Unternehmer im Sinne des § 14 BGB, juristische Personen des öffentlichen\n    Rechts und öffentlich-rechtliche Sondervermögen („Kunde“), insbesondere an Träger von Maßnahmen und selbstständige\n    Coaches.\n- type: individual\n  text: Verbraucher können keinen Vertrag schließen.\nrestricted_uses:\n- summary: Only own measures\n  text: Der Kunde nutzt AZAV-Doku nur für eigene Maßnahmen und\
  \ nur rechtmäßig.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Der Kunde bestätigt bei der Registrierung, dass er als Unternehmer handelt.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/azav-doku-de/eligibility/azav-doku-de-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from AZAV-Doku's own page on 2026-11-09.
synthetic: false
tags:
- AVGS
- Documentation
- Digital Signature
- Free
- German
- Healthcare
---
