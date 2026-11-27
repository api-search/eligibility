---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Per poter usufruire del servizio di prenotazione tramite il sito, è necessaria la registrazione dell’utente.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: Questi dati possono essere scaricati o utilizzati solo per uso personale e non commerciale
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: il sistema richiederà di inserire i dati anagrafici quali nome e cognome, codice fiscale, cellulare con richiesta di verifica tramite OTP, una e-mail valida ed una password
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cup24.it
provenance_date: '2026-11-09'
provider_name: Cup24.it
provider_slug: cup24-it
slug: cup24-it-eligibility
source_date: '2026-11-09'
source_filename: cup24-it-eligibility.yml
source_heading: Eligibility
source_page: https://cup24.it/termini-e-condizioni
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cup24.it\naid: cup24-it\nurl: https://cup24.it/termini-e-condizioni\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Per poter usufruire del servizio di prenotazione tramite il sito, è necessaria la registrazione dell’utente.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: Questi dati possono essere scaricati o utilizzati solo per uso personale e non commerciale\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: il sistema richiederà di inserire i dati anagrafici quali nome e cognome,\
  \ codice fiscale, cellulare con\n    richiesta di verifica tramite OTP, una e-mail valida ed una password\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cup24-it/eligibility/cup24-it-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Cup24.it's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Medical Appointments
- Booking
- Marketplace
- Clinics
- Italy
- MCP
---
