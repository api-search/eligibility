---
api_specs:
- filename: neso-datastore-api-openapi.yml
  format: yaml
  label: National Energy System Operator (NESO) Datastore API
  slug: neso-datastore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neso/openapi/neso-datastore-api-openapi.yml
- filename: neso-discovery-api-openapi.yml
  format: yaml
  label: National Energy System Operator (NESO) Discovery API
  slug: neso-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neso/openapi/neso-discovery-api-openapi.yml
- filename: neso-metadata-api-openapi.yml
  format: yaml
  label: National Energy System Operator (NESO) Metadata API
  slug: neso-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neso/openapi/neso-metadata-api-openapi.yml
- filename: neso-search-api-openapi.yml
  format: yaml
  label: National Energy System Operator (NESO) Search API
  slug: neso-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neso/openapi/neso-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no promise that the Website is appropriate for use in locations outside of the UK.
  entity_types:
  - text: you, the natural or legal person who uses or accesses the Website or the Services and each entity on whose behalf the user acts
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No spam
    text: Use the Website or Services in any way to send unsolicited (commercial or otherwise) e-mail ( Spam ) or any material for marketing or publicity purposes
  - source: https://github.com/carbon-intensity/terms
    summary: Substantive replacement of NESO services
    text: Use the Carbon Intensity API for any application that substantially replaces the core user experience of National Energy System Operator's websites, apps, or the Carbon Intensity API.
  - source: https://github.com/carbon-intensity/terms
    summary: Malicious software
    text: Use the Carbon Intensity API for any application that is spyware, adware, or any other malicious software, or is used in connection with any such software.
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
name: National Energy System Operator (NESO)
provenance_date: '2026-11-10'
provider_name: National Energy System Operator (NESO)
provider_slug: neso
slug: neso-eligibility
source_date: '2026-11-10'
source_filename: neso-eligibility.yml
source_heading: Eligibility
source_page: https://www.neso.energy/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: National Energy System Operator (NESO)\naid: neso\nurl: https://www.neso.energy/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://github.com/carbon-intensity/terms\n  - https://www.neso.energy/terms-and-conditions\ncountries:\n  served: []\n  excluded: []\n  text: We make no promise that the Website is appropriate for use in locations outside of the UK.\nentity_types:\n- type: other\n  text: you, the natural or legal person who uses or accesses the Website or the Services and each entity on whose\n    behalf the user acts\nrestricted_uses:\n- summary: No spam\n  text: Use the Website or\
  \ Services in any way to send unsolicited (commercial or otherwise) e-mail ( Spam ) or\n    any material for marketing or publicity purposes\n- summary: Substantive replacement of NESO services\n  text: Use the Carbon Intensity API for any application that substantially replaces the core user experience of\n    National Energy System Operator's websites, apps, or the Carbon Intensity API.\n  source: https://github.com/carbon-intensity/terms\n- summary: Malicious software\n  text: Use the Carbon Intensity API for any application that is spyware, adware, or any other malicious software,\n    or is used in connection with any such software.\n  source: https://github.com/carbon-intensity/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/neso/eligibility/neso-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from National Energy System Operator (NESO)'s own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United Kingdom
- Electricity
- Energy Markets
- Grid
- Open Data
- Carbon
- Renewables
- Gas
- Demand Response
- Carbon Intensity
---
