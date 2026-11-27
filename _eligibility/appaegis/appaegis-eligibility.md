---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity (“you”)
    type: individual
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or competing use
    text: 'As a user of the Site, you agree not to: 1. Engage in illegal activities.'
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
name: Appaegis
provenance_date: '2026-11-09'
provider_name: Appaegis
provider_slug: appaegis
slug: appaegis-eligibility
source_date: '2026-11-09'
source_filename: appaegis-eligibility.yml
source_heading: Eligibility
source_page: https://mammothcyber.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appaegis\naid: appaegis\nurl: https://mammothcyber.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (“you”)\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Illegal or competing use\n  text: 'As a user of the Site, you\
  \ agree not to: 1. Engage in illegal activities.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appaegis/eligibility/appaegis-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Appaegis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Zero Trust
- Enterprise Browser
- Identity and Access Management
- Data Loss Prevention
- GenAI Security
- Identity
- SASE
---
