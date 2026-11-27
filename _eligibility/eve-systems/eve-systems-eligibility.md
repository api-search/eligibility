---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: Zur Teilnahme an der Aktion sind ausschließlich private Endkunden (Verbraucher) ab 18 Jahren mit Wohnsitz in Deutschland berechtigt.
  entity_types:
  - text: ausschließlich private Endkunden (Verbraucher) ab 18 Jahren
    type: individual
  minimum_age:
    text: ab 18 Jahren
    value: '18'
  restricted_uses:
  - summary: Not combinable with other promotions
    text: Die Teilnahme an der Aktion ist nicht mit anderen Aktionen kombinierbar, insbesondere ist der Einsatz eines zusätzlichen Rabattcodes zur Erwirkung eines weiteren Preisvorteils nicht zulässig.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Der Anbieter behält sich vor, jede Bestellung zu überprüfen und abzulehnen, falls der Kunde nicht teilnahmeberechtigt ist.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Eve Systems
provenance_date: '2026-11-09'
provider_name: Eve Systems
provider_slug: eve-systems
slug: eve-systems-eligibility
source_date: '2026-11-09'
source_filename: eve-systems-eligibility.yml
source_heading: Eligibility
source_page: https://www.evehome.com/en/installationsservice/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eve Systems\naid: eve-systems\nurl: https://www.evehome.com/en/installationsservice/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: Zur Teilnahme an der Aktion sind ausschließlich private Endkunden (Verbraucher) ab 18 Jahren mit Wohnsitz\n    in Deutschland berechtigt.\nentity_types:\n- type: individual\n  text: ausschließlich private Endkunden (Verbraucher) ab 18 Jahren\nrestricted_uses:\n- summary: Not combinable with other promotions\n  text: Die Teilnahme an der Aktion ist nicht mit anderen Aktionen kombinierbar, insbesondere ist der Einsatz eines\n    zusätzlichen\
  \ Rabattcodes zur Erwirkung eines weiteren Preisvorteils nicht zulässig.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Der Anbieter behält sich vor, jede Bestellung zu überprüfen und abzulehnen, falls der Kunde nicht teilnahmeberechtigt\n    ist.\nminimum_age:\n  value: '18'\n  text: ab 18 Jahren\n"
source_yaml_url: https://artifacts.apis.io/eve-systems/eligibility/eve-systems-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Eve Systems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Smart Home
- HomeKit
- IoT
- Energy
- Automation
---
