---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: L’utilizzo dei Servizi è consentito agli Utenti maggiorenni.
    type: individual
  - text: Per Utente Corporate si intende la persona giuridica e/o la ditta individuale che ha sottoscritto uno specifico e separato accordo con Unobravo
    type: business
  minimum_age:
    text: L’utilizzo dei Servizi è consentito agli Utenti maggiorenni.
    value: adult (maggiorenni)
  restricted_uses:
  - summary: No emergency assistance
    text: Unobravo non fornisce assistenza in situazioni di emergenza quali, a titolo esemplificativo, minacce di suicidio
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: L’Utente garantisce la veridicità delle informazioni fornite, che potranno essere verificate da parte di Unobravo
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unobravo
provenance_date: '2026-11-10'
provider_name: Unobravo
provider_slug: unobravo
slug: unobravo-eligibility
source_date: '2026-11-10'
source_filename: unobravo-eligibility.yml
source_heading: Eligibility
source_page: https://www.unobravo.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unobravo\naid: unobravo\nurl: https://www.unobravo.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: L’utilizzo dei Servizi è consentito agli Utenti maggiorenni.\n- type: business\n  text: Per Utente Corporate si intende la persona giuridica e/o la ditta individuale che ha sottoscritto uno specifico\n    e separato accordo con Unobravo\nrestricted_uses:\n- summary: No emergency assistance\n  text: Unobravo non fornisce assistenza in situazioni di emergenza quali, a titolo esemplificativo, minacce di\n    suicidio\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: L’Utente garantisce la veridicità delle informazioni fornite, che potranno essere verificate da parte di\n    Unobravo\nminimum_age:\n  value: adult (maggiorenni)\n  text: L’utilizzo dei Servizi è consentito agli Utenti maggiorenni.\n"
source_yaml_url: https://artifacts.apis.io/unobravo/eligibility/unobravo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Unobravo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Mental Health
- Psychology
- Telehealth
- Online Therapy
- Healthcare
---
