---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Die Software richtet sich ausschließlich an Unternehmer im Sinne von § 14 des Bürgerlichen Gesetzbuches (BGB).
    type: business
  minimum_age:
    text: Der Vertragspartner hat sicherzustellen, dass ausschließlich Nutzer Zugriff zur Software erhalten, die mindestens 18 Jahre alt und geschäftsfähig sind.
    value: '18'
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
name: Meisterwerk
provenance_date: '2026-11-10'
provider_name: Meisterwerk
provider_slug: meisterwerk
slug: meisterwerk-eligibility
source_date: '2026-11-10'
source_filename: meisterwerk-eligibility.yml
source_heading: Eligibility
source_page: https://www.meisterwerk.app/allgemeine-geschaeftsbedingungen
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meisterwerk\naid: meisterwerk\nurl: https://www.meisterwerk.app/allgemeine-geschaeftsbedingungen\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Die Software richtet sich ausschließlich an Unternehmer im Sinne von § 14 des Bürgerlichen Gesetzbuches\n    (BGB).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Der Vertragspartner hat sicherzustellen, dass ausschließlich Nutzer Zugriff zur Software erhalten, die mindestens\n    18 Jahre alt und geschäftsfähig\
  \ sind.\n"
source_yaml_url: https://artifacts.apis.io/meisterwerk/eligibility/meisterwerk-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Meisterwerk's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Trade
- Handwerk
- Field Service Management
- Scheduling
- Time Tracking
- Invoicing
- Construction
- Germany
- DACH
- Mobile
---
