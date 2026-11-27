---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need to be 16 or over to have an account or make an RSVP.
    type: individual
  - text: If you use Events.Aero for a business, for example as an organiser, the most we will pay you for any event is the total fees you have paid us for that event.
    type: business
  minimum_age:
    text: You need to be 16 or over to have an account or make an RSVP.
    value: '16'
  restricted_uses:
  - summary: No ticket resale
    text: You must not sell tickets or advertise them for sale.
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
name: Events.Aero
provenance_date: '2026-11-09'
provider_name: Events.Aero
provider_slug: events-aero
slug: events-aero-eligibility
source_date: '2026-11-09'
source_filename: events-aero-eligibility.yml
source_heading: Eligibility
source_page: https://events.aero/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Events.Aero\naid: events-aero\nurl: https://events.aero/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need to be 16 or over to have an account or make an RSVP.\n- type: business\n  text: If you use Events.Aero for a business, for example as an organiser, the most we will pay you for any event\n    is the total fees you have paid us for that event.\nrestricted_uses:\n- summary: No ticket resale\n  text: You must not sell tickets or advertise them for sale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: You need to be 16 or over to have an account or make an RSVP.\n"
source_yaml_url: https://artifacts.apis.io/events-aero/eligibility/events-aero-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Events.Aero's own page on 2026-11-09.
synthetic: false
tags:
- Aviation
- Event
- Airshows
- Fly-ins
- Community
---
