---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Un cliente professionale usa il Servizio per attività commerciali, imprenditoriali, artigianali o professionali
    type: business
  - text: un consumatore lo usa principalmente per scopi personali
    type: individual
  minimum_age:
    text: Devi avere la capacità legale di stipulare questo accordo.
    value: null
  restricted_uses:
  - summary: Not an emergency service
    text: Non usare il Servizio come servizio di emergenza o come unica protezione contro lesioni o gravi perdite.
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
name: Medifontis
provenance_date: '2026-11-10'
provider_name: Medifontis
provider_slug: medifontis
slug: medifontis-eligibility
source_date: '2026-11-10'
source_filename: medifontis-eligibility.yml
source_heading: Eligibility
source_page: https://www.medifontis.com/it/it/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medifontis\naid: medifontis\nurl: https://www.medifontis.com/it/it/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Un cliente professionale usa il Servizio per attività commerciali, imprenditoriali, artigianali o professionali\n- type: individual\n  text: un consumatore lo usa principalmente per scopi personali\nrestricted_uses:\n- summary: Not an emergency service\n  text: Non usare il Servizio come servizio di emergenza o come unica protezione contro lesioni o gravi perdite.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: Devi avere la capacità legale di stipulare questo accordo.\n"
source_yaml_url: https://artifacts.apis.io/medifontis/eligibility/medifontis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Medifontis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- FDA
- Drugs
---
