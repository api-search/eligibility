---
api_specs:
- filename: university-of-sheffield-admin-api-openapi.yml
  format: yaml
  label: University of Sheffield Admin API
  slug: university-of-sheffield-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-admin-api-openapi.yml
- filename: university-of-sheffield-api-auth-api-openapi.yml
  format: yaml
  label: University of Sheffield API Auth API
  slug: university-of-sheffield-api-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-api-auth-api-openapi.yml
- filename: university-of-sheffield-auth-api-openapi.yml
  format: yaml
  label: University of Sheffield Auth API
  slug: university-of-sheffield-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-auth-api-openapi.yml
- filename: university-of-sheffield-health-api-openapi.yml
  format: yaml
  label: University of Sheffield Health API
  slug: university-of-sheffield-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-health-api-openapi.yml
- filename: university-of-sheffield-metrics-api-openapi.yml
  format: yaml
  label: University of Sheffield Metrics API
  slug: university-of-sheffield-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-metrics-api-openapi.yml
- filename: university-of-sheffield-pvforecast-api-openapi.yml
  format: yaml
  label: University of Sheffield Pvforecast API
  slug: university-of-sheffield-pvforecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-pvforecast-api-openapi.yml
- filename: university-of-sheffield-pvlive-api-openapi.yml
  format: yaml
  label: University of Sheffield Pvlive API
  slug: university-of-sheffield-pvlive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-pvlive-api-openapi.yml
- filename: university-of-sheffield-pvlive-eu-api-openapi.yml
  format: yaml
  label: University of Sheffield Pvlive Eu API
  slug: university-of-sheffield-pvlive-eu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-pvlive-eu-api-openapi.yml
- filename: university-of-sheffield-user-api-openapi.yml
  format: yaml
  label: University of Sheffield User API
  slug: university-of-sheffield-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-user-api-openapi.yml
- filename: university-of-sheffield-users-api-openapi.yml
  format: yaml
  label: University of Sheffield Users API
  slug: university-of-sheffield-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-sheffield/openapi/university-of-sheffield-users-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Participants under 18 are permitted, but must be entered under the care of another participant over 18.
    type: individual
  - text: If you're signing up as a team to The Big Walk, each team member must pay separately.
    type: business
  minimum_age:
    text: Participants under 18 are permitted, but must be entered under the care of another participant over 18.
    value: null
  restricted_uses:
  - summary: Unsuitable for wheelchairs and prams
    text: The route is unsuitable for wheelchairs, prams or pushchairs due to the uneven terrain in the Peak District.
  - summary: Fundraising pledge required
    text: By registering onto the event you pledge to raise a minimum of £200 for Lung Disease research at the University of Sheffield.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your event place will only be confirmed upon receiving your payment. Places will be allocated on a first come, first served basis.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: University of Sheffield
provenance_date: '2026-11-10'
provider_name: University of Sheffield
provider_slug: university-of-sheffield
slug: university-of-sheffield-eligibility
source_date: '2026-11-10'
source_filename: university-of-sheffield-eligibility.yml
source_heading: Eligibility
source_page: https://sheffield.ac.uk/giving/fundraise/big-walk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: University of Sheffield\naid: university-of-sheffield\nurl: https://sheffield.ac.uk/giving/fundraise/big-walk/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Participants under 18 are permitted, but must be entered under the care of another participant over 18.\n- type: business\n  text: If you're signing up as a team to The Big Walk, each team member must pay separately.\nrestricted_uses:\n- summary: Unsuitable for wheelchairs and prams\n  text: The route is unsuitable for wheelchairs, prams or pushchairs due\
  \ to the uneven terrain in the Peak District.\n- summary: Fundraising pledge required\n  text: By registering onto the event you pledge to raise a minimum of £200 for Lung Disease research at the University\n    of Sheffield.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your event place will only be confirmed upon receiving your payment. Places will be allocated on a first\n    come, first served basis.\nminimum_age:\n  value: null\n  text: Participants under 18 are permitted, but must be entered under the care of another participant over 18.\n"
source_yaml_url: https://artifacts.apis.io/university-of-sheffield/eligibility/university-of-sheffield-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from University of Sheffield's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- United Kingdom
- Russell Group
- Research Data
- Open Access
- OAI-PMH
- Identity Federation
- Solar Energy
- Energy Data
- Research Computing
---
