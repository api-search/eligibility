---
api_specs:
- filename: jetify-pkg-api-openapi.yml
  format: yaml
  label: Jetify Pkg API
  slug: jetify-pkg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetify/openapi/jetify-pkg-api-openapi.yml
- filename: jetify-resolve-api-openapi.yml
  format: yaml
  label: Jetify Resolve API
  slug: jetify-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetify/openapi/jetify-resolve-api-openapi.yml
- filename: jetify-search-api-openapi.yml
  format: yaml
  label: Jetify Search API
  slug: jetify-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetify/openapi/jetify-search-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Jetify from its facilities in the United States of America. Jetify makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: you have the authority to enter into the Agreement personally or on behalf of the legal entity identified during the account registration process
    type: business
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Prohibited user conduct
    text: you agree not to use any of the Services for any purpose that is prohibited by this Agreement or by applicable law
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
name: Jetify
provenance_date: '2026-11-09'
provider_name: Jetify
provider_slug: jetify
slug: jetify-eligibility
source_date: '2026-11-09'
source_filename: jetify-eligibility.yml
source_heading: Eligibility
source_page: https://www.jetify.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jetify\naid: jetify\nurl: https://www.jetify.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Jetify from its facilities in the United States of America. Jetify\n    makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: you have the authority to enter into the Agreement personally or on behalf of the legal entity identified\n    during the account registration process\nrestricted_uses:\n- summary: Prohibited user conduct\n\
  \  text: you agree not to use any of the Services for any purpose that is prohibited by this Agreement or by applicable\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/jetify/eligibility/jetify-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Jetify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Developer Tools
- Nix
- Package Management
- Developer Environments
- Reproducible Builds
- CLI
- Search
---
