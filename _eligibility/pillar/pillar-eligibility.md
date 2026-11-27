---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: È consentita la registrazione solamente alle persone giuridiche e fisiche che utilizzano la Piattaforma con finalità riferibili alla loro attività commerciale, imprenditoriale o professionale.
    type: business
  - text: È consentita la registrazione solamente alle persone giuridiche e fisiche che utilizzano la Piattaforma con finalità riferibili alla loro attività commerciale, imprenditoriale o professionale.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial, business or professional use only
    text: È consentita la registrazione solamente alle persone giuridiche e fisiche che utilizzano la Piattaforma con finalità riferibili alla loro attività commerciale, imprenditoriale o professionale.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: A seguito dell'approvazione della registrazione alla Piattaforma da parte della Società, che potrà richiedere fino a 7 giorni lavorativi
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pillar
provenance_date: '2026-11-10'
provider_name: Pillar
provider_slug: pillar
slug: pillar-eligibility
source_date: '2026-11-10'
source_filename: pillar-eligibility.yml
source_heading: Eligibility
source_page: https://www.pillar.it/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pillar\naid: pillar\nurl: https://www.pillar.it/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: È consentita la registrazione solamente alle persone giuridiche e fisiche che utilizzano la Piattaforma\n    con finalità riferibili alla loro attività commerciale, imprenditoriale o professionale.\n- type: individual\n  text: È consentita la registrazione solamente alle persone giuridiche e fisiche che utilizzano la Piattaforma\n    con finalità riferibili alla loro attività commerciale, imprenditoriale o professionale.\n\
  restricted_uses:\n- summary: Commercial, business or professional use only\n  text: È consentita la registrazione solamente alle persone giuridiche e fisiche che utilizzano la Piattaforma\n    con finalità riferibili alla loro attività commerciale, imprenditoriale o professionale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: A seguito dell'approvazione della registrazione alla Piattaforma da parte della Società, che potrà richiedere\n    fino a 7 giorni lavorativi\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pillar/eligibility/pillar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Pillar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction
- Construction Technology
- Vertical SaaS
- Invoicing
- Cash Flow Management
- Procurement
- Project Management
- Field Management
- Artificial Intelligence
- Italy
---
