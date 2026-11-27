---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is controlled from offices within the United States. Cinemark makes no representation that content or materials in the Service are appropriate or available for use in other jurisdictions.
  entity_types:
  - text: you are at least thirteen (13) years of age as a user of the Site or App, and a least sixteen (16) years of age as a participant in the Cinemark Movie Rewards Program
    type: individual
  minimum_age:
    text: you are at least thirteen (13) years of age as a user of the Site or App
    value: '13'
  restricted_uses:
  - summary: Illegal use / unlawful jurisdictions
    text: Access to the Service, content, or materials from jurisdictions where such access is illegal is strictly prohibited.
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
name: Cinemark Holdings
provenance_date: '2026-11-09'
provider_name: Cinemark Holdings
provider_slug: cinemark-holdings
slug: cinemark-holdings-eligibility
source_date: '2026-11-09'
source_filename: cinemark-holdings-eligibility.yml
source_heading: Eligibility
source_page: https://www.cinemark.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cinemark Holdings\naid: cinemark-holdings\nurl: https://www.cinemark.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is controlled from offices within the United States. Cinemark makes no representation that content\n    or materials in the Service are appropriate or available for use in other jurisdictions.\nentity_types:\n- type: individual\n  text: you are at least thirteen (13) years of age as a user of the Site or App, and a least sixteen (16) years\n    of age as a participant in the Cinemark Movie Rewards Program\nrestricted_uses:\n- summary:\
  \ Illegal use / unlawful jurisdictions\n  text: Access to the Service, content, or materials from jurisdictions where such access is illegal is strictly\n    prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are at least thirteen (13) years of age as a user of the Site or App\n"
source_yaml_url: https://artifacts.apis.io/cinemark-holdings/eligibility/cinemark-holdings-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cinemark Holdings's own page on 2026-11-09.
synthetic: false
tags:
- Cinema
- Entertainment
- Loyalty
- Movie Theaters
- Ticketing
- Fortune 1000
---
