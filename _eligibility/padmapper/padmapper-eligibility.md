---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: PadMapper does not represent or warrant that use of the Website or Services is lawful in other jurisdictions. If you gain access to the Services from locations outside the United States, you will be responsible for compliance with all local laws of any such other location
  entity_types:
  - text: The Website and the Services are offered and available to users who are 18 years of age or older.
    type: individual
  - text: If the individual clicking to accept or agree to this Agreement is doing so on behalf of an entity and registers such entity with this Website, then you (the individual) represent and warrant that you have authority to bind such entity
    type: business
  minimum_age:
    text: The Website and the Services are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Discriminatory listings
    text: shall not state any discriminatory preference based on race, color, national origin, religion, sex, familial status, handicap or based on any other characteristic prohibited by state or local law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: PadMapper does not conduct any screening, background investigations or credit checks on any individual's character, creditworthiness or rental history
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PadMapper
provenance_date: '2026-11-10'
provider_name: PadMapper
provider_slug: padmapper
slug: padmapper-eligibility
source_date: '2026-11-10'
source_filename: padmapper-eligibility.yml
source_heading: Eligibility
source_page: https://www.padmapper.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PadMapper\naid: padmapper\nurl: https://www.padmapper.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: PadMapper does not represent or warrant that use of the Website or Services is lawful in other jurisdictions.\n    If you gain access to the Services from locations outside the United States, you will be responsible for compliance\n    with all local laws of any such other location\nentity_types:\n- type: individual\n  text: The Website and the Services are offered and available to users who are 18 years of age or older.\n- type: business\n  text: If the individual clicking\
  \ to accept or agree to this Agreement is doing so on behalf of an entity and registers\n    such entity with this Website, then you (the individual) represent and warrant that you have authority to bind\n    such entity\nrestricted_uses:\n- summary: Discriminatory listings\n  text: shall not state any discriminatory preference based on race, color, national origin, religion, sex, familial\n    status, handicap or based on any other characteristic prohibited by state or local law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: PadMapper does not conduct any screening, background investigations or credit checks on any individual's\n    character, creditworthiness or rental history\nminimum_age:\n  value: '18'\n  text: The Website and the Services are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/padmapper/eligibility/padmapper-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from PadMapper's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Rental Listings
- Apartment Search
- Map-Based Search
- Housing
- Property Discovery
- Rental Market Data
---
