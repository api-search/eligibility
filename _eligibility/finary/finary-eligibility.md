---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The opening of a User Account is conditional on principal residence and nationality in a country located in the European Union or within the European Economic Area, or in a country that is not on the list of countries under international sanctions
  entity_types:
  - text: A User may be a natural person with full legal capacity
    type: individual
  - text: or a legal entity acting through a natural person who holds the power or authorisation required to contract in the name and on behalf of the User.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited conduct
    text: 'It is strictly prohibited to use the Services for the following purposes: Carrying on illegal or fraudulent activities or activities infringing the rights or security of third parties;'
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Finary carries out these procedures with respect to any User or person wishing to access Finary's Services. This process applies to both natural persons and legal entities.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Finary
provenance_date: '2026-11-09'
provider_name: Finary
provider_slug: finary
slug: finary-eligibility
source_date: '2026-11-09'
source_filename: finary-eligibility.yml
source_heading: Eligibility
source_page: https://finary.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finary\naid: finary\nurl: https://finary.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The opening of a User Account is conditional on principal residence and nationality in a country located\n    in the European Union or within the European Economic Area, or in a country that is not on the list of countries\n    under international sanctions\nentity_types:\n- type: individual\n  text: A User may be a natural person with full legal capacity\n- type: business\n  text: or a legal entity acting through a natural person who holds the power or authorisation\
  \ required to contract\n    in the name and on behalf of the User.\nrestricted_uses:\n- summary: Prohibited conduct\n  text: 'It is strictly prohibited to use the Services for the following purposes: Carrying on illegal or fraudulent\n    activities or activities infringing the rights or security of third parties;'\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Finary carries out these procedures with respect to any User or person wishing to access Finary's Services.\n    This process applies to both natural persons and legal entities.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/finary/eligibility/finary-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Finary's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Wealth Management
- Personal Finance
- Investing
- Cryptocurrency
- Net Worth Tracking
- Account Aggregation
- Budgeting
---
