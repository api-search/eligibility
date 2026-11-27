---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: utenti inserzionisti privati o professionali
    type: individual
  - text: utenti inserzionisti privati o professionali
    type: business
  minimum_age:
    text: L’utilizzo del Servizio è consentito solo ad utenti maggiorenni secondo la legge italiana (maggiori di anni 18).
    value: '18'
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: il Servizio richiederà, per finalità di revisione e sicurezza, il completamento di una specifica procedura di identificazione prima di procedere alla pubblicazione degli annunci
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Subito.it
provenance_date: '2026-11-10'
provider_name: Subito.it
provider_slug: subito
slug: subito-eligibility
source_date: '2026-11-10'
source_filename: subito-eligibility.yml
source_heading: Eligibility
source_page: https://info.subito.it/policies/condizioni-generali.htm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Subito.it\naid: subito\nurl: https://info.subito.it/policies/condizioni-generali.htm\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: utenti inserzionisti privati o professionali\n- type: business\n  text: utenti inserzionisti privati o professionali\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: il Servizio richiederà, per finalità di revisione e sicurezza, il completamento di una specifica procedura\n    di identificazione prima di procedere alla pubblicazione degli annunci\nminimum_age:\n\
  \  value: '18'\n  text: L’utilizzo del Servizio è consentito solo ad utenti maggiorenni secondo la legge italiana (maggiori di anni\n    18).\n"
source_yaml_url: https://artifacts.apis.io/subito/eligibility/subito-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Subito.it's own page on 2026-11-10.
synthetic: false
tags:
- Marketplace
- Classifieds
- E-Commerce
- Italy
- Recommerce
---
