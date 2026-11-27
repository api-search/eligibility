---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not a resident of (and you will not use the Website in) a country that the U.S. or any other relevant government has embargoed for use of the Website
  entity_types:
  - text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD, BUT IN ANY EVENT OF A LEGAL AGE TO FORM A BINDING CONTRACT.
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY, AND CAPACITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Infringing or unlawful use
    text: use any Exodigo Materials to infringe, misappropriate or violate any third party's Intellectual Property Rights
  - summary: Advertising on the website
    text: upload or publish any advertisement or promotional material on the Website
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
name: Exodigo
provenance_date: '2026-11-09'
provider_name: Exodigo
provider_slug: exodigo
slug: exodigo-eligibility
source_date: '2026-11-09'
source_filename: exodigo-eligibility.yml
source_heading: Eligibility
source_page: https://www.exodigo.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Exodigo\naid: exodigo\nurl: https://www.exodigo.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not a resident of (and you will not use the Website in) a country that the U.S. or any other relevant\n    government has embargoed for use of the Website\nentity_types:\n- type: individual\n  text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD, BUT IN ANY EVENT OF A LEGAL AGE TO FORM A BINDING\n    CONTRACT.\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, YOU REPRESENT THAT YOU HAVE THE RIGHT, AUTHORITY,\n\
  \    AND CAPACITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Infringing or unlawful use\n  text: use any Exodigo Materials to infringe, misappropriate or violate any third party's Intellectual Property\n    Rights\n- summary: Advertising on the website\n  text: upload or publish any advertisement or promotional material on the Website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/exodigo/eligibility/exodigo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Exodigo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Subsurface
- Underground Mapping
- Geophysics
- Infrastructure
- Construction
- Utilities
- Geospatial
- Artificial Intelligence
- Engineering Services
---
