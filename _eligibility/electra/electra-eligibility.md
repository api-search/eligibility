---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Site.
    type: individual
  - text: 'If you are accessing the Site on behalf of an entity, organization, or company, then: (a) “you” will refer to that entity, organization, or company'
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal use or access
    text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.
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
name: Electra
provenance_date: '2026-11-09'
provider_name: Electra
provider_slug: electra
slug: electra-eligibility
source_date: '2026-11-09'
source_filename: electra-eligibility.yml
source_heading: Eligibility
source_page: https://www.electra.earth/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Electra\naid: electra\nurl: https://www.electra.earth/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site.\n- type: business\n  text: 'If you are accessing the Site on behalf of an entity, organization, or company, then: (a) “you” will refer\n    to that entity, organization, or company'\nrestricted_uses:\n\
  - summary: Illegal use or access\n  text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/electra/eligibility/electra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Electra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Clean Energy
- Climate Tech
- Industrial
- Manufacturing
- Materials
- Iron
- Steel
- Decarbonization
- Electrochemistry
- Mining
---
