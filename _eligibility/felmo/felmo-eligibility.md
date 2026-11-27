---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Das Angebot richtet sich ausschließlich an Verbraucher i. S. d. § 13 BGB.
    type: individual
  - text: Das Angebot richtet sich an Besitzer von Hunden und Katzen
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Der Anbieter behält sich u. a. das Recht vor, die Vertragsannahme zu verweigern, sofern die Bonitätsprüfung des Nutzers negativ ausfällt.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Felmo
provenance_date: '2026-11-09'
provider_name: Felmo
provider_slug: felmo
slug: felmo-eligibility
source_date: '2026-11-09'
source_filename: felmo-eligibility.yml
source_heading: Eligibility
source_page: https://felmo.de/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Felmo\naid: felmo\nurl: https://felmo.de/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Das Angebot richtet sich ausschließlich an Verbraucher i. S. d. § 13 BGB.\n- type: individual\n  text: Das Angebot richtet sich an Besitzer von Hunden und Katzen\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Der Anbieter behält sich u. a. das Recht vor, die Vertragsannahme zu verweigern, sofern die Bonitätsprüfung\n    des Nutzers negativ ausfällt.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/felmo/eligibility/felmo-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Felmo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Veterinary
- Consumer
- Pet Care
- Mobile Health
- Germany
---
