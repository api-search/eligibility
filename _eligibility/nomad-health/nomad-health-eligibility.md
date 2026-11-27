---
api_specs:
- filename: nomad-health-default-api-openapi.yml
  format: yaml
  label: Nomad Health Default API
  slug: nomad-health-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nomad-health/openapi/nomad-health-default-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims that the Sites are accessible or appropriate outside of the United States.
  entity_types:
  - text: you are a United States resident of at least 18 years of age with the right and capacity to form a legally binding contract
    type: individual
  - text: If you use the Sites on behalf of a legal entity, you represent that you are a duly authorized representative with the authority to bind that legal entity to these Terms.
    type: business
  minimum_age:
    text: you are a United States resident of at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unauthorized security testing
    text: Attempting to probe, scan or test the vulnerability of a system or network or to breach security or authentication measures without proper authorization
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
name: Nomad Health
provenance_date: '2026-11-10'
provider_name: Nomad Health
provider_slug: nomad-health
slug: nomad-health-eligibility
source_date: '2026-11-10'
source_filename: nomad-health-eligibility.yml
source_heading: Eligibility
source_page: https://nomadhealth.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nomad Health\naid: nomad-health\nurl: https://nomadhealth.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims that the Sites are accessible or appropriate outside of the United States.\nentity_types:\n- type: individual\n  text: you are a United States resident of at least 18 years of age with the right and capacity to form a legally\n    binding contract\n- type: business\n  text: If you use the Sites on behalf of a legal entity, you represent that you are a duly authorized representative\n    with the authority to bind that legal entity to these Terms.\nrestricted_uses:\n\
  - summary: Unauthorized security testing\n  text: Attempting to probe, scan or test the vulnerability of a system or network or to breach security or authentication\n    measures without proper authorization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are a United States resident of at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/nomad-health/eligibility/nomad-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nomad Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Staffing
- Job
- Marketplace
- Travel Nursing
- Allied Health
- Credentialing
- Recruiting
- Human Resources
---
