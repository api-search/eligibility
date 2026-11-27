---
api_specs:
- filename: one-degree-housing-api-openapi.yml
  format: yaml
  label: One Degree Housing API
  slug: one-degree-housing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/one-degree/openapi/one-degree-housing-api-openapi.yml
- filename: one-degree-locations-api-openapi.yml
  format: yaml
  label: One Degree Locations API
  slug: one-degree-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/one-degree/openapi/one-degree-locations-api-openapi.yml
- filename: one-degree-opportunities-api-openapi.yml
  format: yaml
  label: One Degree Opportunities API
  slug: one-degree-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/one-degree/openapi/one-degree-opportunities-api-openapi.yml
- filename: one-degree-organizations-api-openapi.yml
  format: yaml
  label: One Degree Organizations API
  slug: one-degree-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/one-degree/openapi/one-degree-organizations-api-openapi.yml
- filename: one-degree-reference-api-openapi.yml
  format: yaml
  label: One Degree Reference API
  slug: one-degree-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/one-degree/openapi/one-degree-reference-api-openapi.yml
- filename: one-degree-submissions-api-openapi.yml
  format: yaml
  label: One Degree Submissions API
  slug: one-degree-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/one-degree/openapi/one-degree-submissions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site may not be appropriate or available for use in some jurisdictions outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Advertising or selling without consent
    text: Use the Site to advertise or offer to sell or buy any goods or services without Company’s express prior written consent.
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
name: One Degree
provenance_date: '2026-11-10'
provider_name: One Degree
provider_slug: one-degree
slug: one-degree-eligibility
source_date: '2026-11-10'
source_filename: one-degree-eligibility.yml
source_heading: Eligibility
source_page: https://about.1degree.org/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: One Degree\naid: one-degree\nurl: https://about.1degree.org/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site may not be appropriate or available for use in some jurisdictions outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Advertising or selling without consent\n  text: Use the Site to advertise or offer to sell or buy any goods or services without Company’s express prior\n    written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/one-degree/eligibility/one-degree-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from One Degree's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Non-Profit
- Social Services
- Community Resources
- Human Services
- Public-benefit
- Housing
- Open Data
- Civic Tech
---
