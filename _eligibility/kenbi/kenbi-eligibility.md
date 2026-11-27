---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Diese AGB gelten gegenüber Verbrauchern und Unternehmern im Sinne der §§ 13, 14 BGB.
    type: individual
  - text: Diese AGB gelten gegenüber Verbrauchern und Unternehmern im Sinne der §§ 13, 14 BGB.
    type: business
  minimum_age:
    text: Der Kunde versichert mit der Buchung, dass er mindestens 18 Jahre alt ist
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Der Anbieter ist berechtigt, Buchungsanfragen im Einzelfall ohne Angabe von Gründen abzulehnen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kenbi
provenance_date: '2026-11-09'
provider_name: Kenbi
provider_slug: kenbi
slug: kenbi-eligibility
source_date: '2026-11-09'
source_filename: kenbi-eligibility.yml
source_heading: Eligibility
source_page: https://kenbi-akademie.com/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kenbi\naid: kenbi\nurl: https://kenbi-akademie.com/agb/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Diese AGB gelten gegenüber Verbrauchern und Unternehmern im Sinne der §§ 13, 14 BGB.\n- type: business\n  text: Diese AGB gelten gegenüber Verbrauchern und Unternehmern im Sinne der §§ 13, 14 BGB.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Der Anbieter ist berechtigt, Buchungsanfragen im Einzelfall ohne Angabe von Gründen abzulehnen.\nminimum_age:\n  value: '18'\n  text: Der\
  \ Kunde versichert mit der Buchung, dass er mindestens 18 Jahre alt ist\n"
source_yaml_url: https://artifacts.apis.io/kenbi/eligibility/kenbi-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Kenbi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Nursing
- Education
- Training
- Germany
---
