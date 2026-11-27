---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation or warranty that the information on the Site is appropriate or available for use in other jurisdictions, and access to our Site from jurisdictions where the content of our Site may be illegal is prohibited.
  entity_types:
  - text: You must be at least 18 years old to use the Services.
    type: individual
  - text: THE END USER (ON BEHALF OF YOURSELF, OR YOUR COMPANY OR ORGANIZATION)
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Access from jurisdictions where content may be illegal
    text: access to our Site from jurisdictions where the content of our Site may be illegal is prohibited.
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
name: Avenzo Therapeutics
provenance_date: '2026-11-09'
provider_name: Avenzo Therapeutics
provider_slug: avenzo
slug: avenzo-eligibility
source_date: '2026-11-09'
source_filename: avenzo-eligibility.yml
source_heading: Eligibility
source_page: https://avenzotx.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avenzo Therapeutics\naid: avenzo\nurl: https://avenzotx.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation or warranty that the information on the Site is appropriate or available for use\n    in other jurisdictions, and access to our Site from jurisdictions where the content of our Site may be illegal\n    is prohibited.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services.\n- type: business\n  text: THE END USER (ON BEHALF OF YOURSELF, OR YOUR COMPANY OR ORGANIZATION)\nrestricted_uses:\n-\
  \ summary: Access from jurisdictions where content may be illegal\n  text: access to our Site from jurisdictions where the content of our Site may be illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/avenzo/eligibility/avenzo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Avenzo Therapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Oncology
- Therapeutics
- Clinical Trials
- Innovation
- Healthcare
---
