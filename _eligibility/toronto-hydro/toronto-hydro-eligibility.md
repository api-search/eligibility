---
api_specs:
- filename: toronto-hydro-applicationinformation-api-openapi.yml
  format: yaml
  label: Toronto Hydro Application Information API
  slug: toronto-hydro-applicationinformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toronto-hydro/openapi/toronto-hydro-applicationinformation-api-openapi.yml
- filename: toronto-hydro-authorization-api-openapi.yml
  format: yaml
  label: Toronto Hydro Authorization API
  slug: toronto-hydro-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toronto-hydro/openapi/toronto-hydro-authorization-api-openapi.yml
- filename: toronto-hydro-batch-api-openapi.yml
  format: yaml
  label: Toronto Hydro Batch API
  slug: toronto-hydro-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toronto-hydro/openapi/toronto-hydro-batch-api-openapi.yml
- filename: toronto-hydro-usagepoint-api-openapi.yml
  format: yaml
  label: Toronto Hydro Usage Point API
  slug: toronto-hydro-usagepoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toronto-hydro/openapi/toronto-hydro-usagepoint-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using this Site, you represent and warrant that you are the legal age of majority under applicable law to form a binding contract with Toronto Hydro
    type: individual
  - source: https://www.torontohydro.com/green-button/third-party-terms
    text: the third-party entity that is the subject of the application
    type: other
  minimum_age:
    text: you are the legal age of majority under applicable law to form a binding contract with Toronto Hydro
    value: age of majority
  restricted_uses:
  - summary: Green Button active customers only
    text: use of any Green Button functionality is available to active Toronto Hydro customers only
  - source: https://www.torontohydro.com/green-button/third-party-terms
    summary: Unlawful or prohibited use
    text: You may not access or use the Subject Matter for any purpose that is unlawful or that is prohibited by these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration is required in order to access the Portal and use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Toronto Hydro
provenance_date: '2026-11-10'
provider_name: Toronto Hydro
provider_slug: toronto-hydro
slug: toronto-hydro-eligibility
source_date: '2026-11-10'
source_filename: toronto-hydro-eligibility.yml
source_heading: Eligibility
source_page: https://www.torontohydro.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Toronto Hydro\naid: toronto-hydro\nurl: https://www.torontohydro.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.torontohydro.com/green-button/third-party-terms\n  - https://www.torontohydro.com/terms-conditions\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using this Site, you represent and warrant that you are the legal age of majority under applicable law\n    to form a binding contract with Toronto Hydro\n- type: other\n  text: the third-party entity that is the subject of the application\n  source: https://www.torontohydro.com/green-button/third-party-terms\n\
  restricted_uses:\n- summary: Green Button active customers only\n  text: use of any Green Button functionality is available to active Toronto Hydro customers only\n- summary: Unlawful or prohibited use\n  text: You may not access or use the Subject Matter for any purpose that is unlawful or that is prohibited by these\n    Terms.\n  source: https://www.torontohydro.com/green-button/third-party-terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration is required in order to access the Portal and use the Services.\nminimum_age:\n  value: age of majority\n  text: you are the legal age of majority under applicable law to form a binding contract with Toronto Hydro\n"
source_yaml_url: https://artifacts.apis.io/toronto-hydro/eligibility/toronto-hydro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Toronto Hydro's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- Canada
- Utilities
- Electricity
- Smart Metering
- Green Button
- Grid
- Ontario
- Consumer Data
- Electricity Distribution
---
