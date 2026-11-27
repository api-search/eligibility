---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: Das Angebot von RABOT ENERGY richtet sich ausdrücklich nur an solche Kunden, die ihre Stromverbrauchsstelle in Deutschland haben
  entity_types:
  - text: Gewerbekunden mit einem Stromverbrauch bis zu 100.000 kWh pro Abrechnungsjahr
    type: business
  minimum_age:
    text: Neukunden sind volljährige Personen, die noch nicht Kunden von RABOT ENERGY waren.
    value: '18'
  restricted_uses:
  - summary: Referral program limits
    text: Firmen-/Unternehmer- und Geschäftskunden können am Kunden werben Kunden-Programm leider nicht teilnehmen, es sei denn, es besteht eine private Geschäftsbeziehung zu RABOT ENERGY, über die KwK genutzt werden kann.
  - summary: No mass recruiting of new customers
    text: Das massenweise Anwerben von Neukunden (z. B. über Vermittlerportale etc.) ist untersagt und berechtigt nicht zum Erhalt von Prämien.
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
name: rabot.energy
provenance_date: '2026-11-10'
provider_name: rabot.energy
provider_slug: rabotenergy
slug: rabotenergy-eligibility
source_date: '2026-11-10'
source_filename: rabotenergy-eligibility.yml
source_heading: Eligibility
source_page: https://www.rabot.energy/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rabot.energy\naid: rabotenergy\nurl: https://www.rabot.energy/agb/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: Das Angebot von RABOT ENERGY richtet sich ausdrücklich nur an solche Kunden, die ihre Stromverbrauchsstelle\n    in Deutschland haben\nentity_types:\n- type: business\n  text: Gewerbekunden mit einem Stromverbrauch bis zu 100.000 kWh pro Abrechnungsjahr\nrestricted_uses:\n- summary: Referral program limits\n  text: Firmen-/Unternehmer- und Geschäftskunden können am Kunden werben Kunden-Programm leider nicht teilnehmen,\n    es sei denn, es besteht eine private Geschäftsbeziehung\
  \ zu RABOT ENERGY, über die KwK genutzt werden kann.\n- summary: No mass recruiting of new customers\n  text: Das massenweise Anwerben von Neukunden (z. B. über Vermittlerportale etc.) ist untersagt und berechtigt\n    nicht zum Erhalt von Prämien.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Neukunden sind volljährige Personen, die noch nicht Kunden von RABOT ENERGY waren.\n"
source_yaml_url: https://artifacts.apis.io/rabotenergy/eligibility/rabotenergy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from rabot.energy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Energy
- Electricity
- Utilities
- Renewable Energy
- Smart Meter
- EV Charging
- Germany
- Dynamic Pricing
---
