---
api_specs:
- filename: one-concern-location-api-openapi.yml
  format: yaml
  label: One Concern Location API
  slug: one-concern-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/one-concern/openapi/one-concern-location-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - JP
    text: You must be 13 years of age or older and reside in the United States or Japan or any of their respective territories to use our Services.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity with the authority to bind the entity to these Terms
    type: business
  minimum_age:
    text: You must be 13 years of age or older and reside in the United States or Japan
    value: '13'
  restricted_uses:
  - summary: Illegal, harassing or disruptive use
    text: use the Services for illegal, harassing, unethical, or disruptive purposes
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
name: One Concern
provenance_date: '2026-11-10'
provider_name: One Concern
provider_slug: one-concern
slug: one-concern-eligibility
source_date: '2026-11-10'
source_filename: one-concern-eligibility.yml
source_heading: Eligibility
source_page: https://oneconcern.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: One Concern\naid: one-concern\nurl: https://oneconcern.com/en/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - JP\n  excluded: []\n  text: You must be 13 years of age or older and reside in the United States or Japan or any of their respective\n    territories to use our Services.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of the entity with the authority\n    to bind the entity to these Terms\nrestricted_uses:\n\
  - summary: Illegal, harassing or disruptive use\n  text: use the Services for illegal, harassing, unethical, or disruptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older and reside in the United States or Japan\n"
source_yaml_url: https://artifacts.apis.io/one-concern/eligibility/one-concern-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from One Concern's own page on 2026-11-10.
synthetic: false
tags:
- Climate Risk
- Catastrophe Modeling
- Resilience
- Insurance
- Reinsurance
- Risk Analytics
- Geospatial
- Business Interruption
- Real Estate
- Financial Services
- Artificial Intelligence
---
