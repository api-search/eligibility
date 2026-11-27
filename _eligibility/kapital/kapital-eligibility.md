---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: El Usuario reconoce que algunos de los Servicios no estarán disponibles en todas las áreas geográficas
  entity_types:
  - text: El Sitio se ofrece para que el Usuario haga uso personal de los Servicios
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Kapital
provenance_date: '2026-11-09'
provider_name: Kapital
provider_slug: kapital
slug: kapital-eligibility
source_date: '2026-11-09'
source_filename: kapital-eligibility.yml
source_heading: Eligibility
source_page: https://kapital.com/recursos/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kapital\naid: kapital\nurl: https://kapital.com/recursos/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: El Usuario reconoce que algunos de los Servicios no estarán disponibles en todas las áreas geográficas\nentity_types:\n- type: individual\n  text: El Sitio se ofrece para que el Usuario haga uso personal de los Servicios\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kapital/eligibility/kapital-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Kapital's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Financial Services
- Fintech
- Small and Medium Businesses
- Payments
- Foreign Exchange
- Lending
- Treasury
- Artificial Intelligence
- Mexico
- Latin America
---
