---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unser Angebot richtet sich an Verbraucher.
    type: individual
  minimum_age:
    text: Konto-Inhaber und Vertragspartner müssen volljährig sein
    value: volljährig
  restricted_uses:
  - summary: Keine medizinischen Leistungen
    text: Behandlungspflege, Heilbehandlung und medizinische Leistungen sind nicht Bestandteil.
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
name: Careship
provenance_date: '2026-11-09'
provider_name: Careship
provider_slug: careship
slug: careship-eligibility
source_date: '2026-11-09'
source_filename: careship-eligibility.yml
source_heading: Eligibility
source_page: https://www.careship.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Careship\naid: careship\nurl: https://www.careship.de/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Unser Angebot richtet sich an Verbraucher.\nrestricted_uses:\n- summary: Keine medizinischen Leistungen\n  text: Behandlungspflege, Heilbehandlung und medizinische Leistungen sind nicht Bestandteil.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: volljährig\n  text: Konto-Inhaber und Vertragspartner müssen volljährig sein\n"
source_yaml_url: https://artifacts.apis.io/careship/eligibility/careship-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Careship's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Elder Care
- Senior Care
- Caregiving
- Marketplace
- Germany
- Home Care
---
