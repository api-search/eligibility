---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will not permit users to access or use the Services in a U.S.-embargoed country or in violation of any U.S. export law or regulation.
  entity_types:
  - text: If You are entering into this Agreement on behalf of a company or other legal entity, You represent and warrant that You have the authority to bind such entity
    type: business
  - text: If You do not have such authority or a legal entity does not exist, You are personally responsible for the obligations hereunder.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Cannabis/CBD/illegal goods texting ban
    text: If Your business involves the marketing or sale of cannabis, CBD, kratom, drug paraphernalia products, or illegal substances or articles, You are prohibited from using the text messaging feature of the Services
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
name: Popmenu
provenance_date: '2026-11-10'
provider_name: Popmenu
provider_slug: popmenu
slug: popmenu-eligibility
source_date: '2026-11-10'
source_filename: popmenu-eligibility.yml
source_heading: Eligibility
source_page: https://my.popmenu.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Popmenu\naid: popmenu\nurl: https://my.popmenu.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You will not permit users to access or use the Services in a U.S.-embargoed country or in violation of any\n    U.S. export law or regulation.\nentity_types:\n- type: business\n  text: If You are entering into this Agreement on behalf of a company or other legal entity, You represent and\n    warrant that You have the authority to bind such entity\n- type: individual\n  text: If You do not have such authority or a legal entity does not exist, You are personally responsible for\
  \ the\n    obligations hereunder.\nrestricted_uses:\n- summary: Cannabis/CBD/illegal goods texting ban\n  text: If Your business involves the marketing or sale of cannabis, CBD, kratom, drug paraphernalia products, or\n    illegal substances or articles, You are prohibited from using the text messaging feature of the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/popmenu/eligibility/popmenu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Popmenu's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Menus
- Online Ordering
- Websites
- Marketing
- Integration
- Hospitality
- GraphQL
- Point-of-Sale
- Reservations
- Loyalty
- AI Marketing
---
