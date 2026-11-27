---
api_specs:
- filename: hivemapper-account-api-openapi.yml
  format: yaml
  label: Hivemapper Account API
  slug: hivemapper-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-account-api-openapi.yml
- filename: hivemapper-ai-events-api-openapi.yml
  format: yaml
  label: Hivemapper AI Events API
  slug: hivemapper-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-ai-events-api-openapi.yml
- filename: hivemapper-bursts-api-openapi.yml
  format: yaml
  label: Hivemapper Bursts API
  slug: hivemapper-bursts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-bursts-api-openapi.yml
- filename: hivemapper-imagery-api-openapi.yml
  format: yaml
  label: Hivemapper Imagery API
  slug: hivemapper-imagery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-imagery-api-openapi.yml
- filename: hivemapper-map-features-api-openapi.yml
  format: yaml
  label: Hivemapper Map Features API
  slug: hivemapper-map-features-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-map-features-api-openapi.yml
- filename: hivemapper-devices-api-openapi.yml
  format: yaml
  label: Hivemapper Devices API
  slug: hivemapper-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hivemapper/openapi/hivemapper-devices-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to participate in the Network. If you are under 18, you represent that you have your parent or guardian's permission to participate
    type: individual
  - text: If you are participating on behalf of a company or organization, you represent that you have authority to bind that entity to this Agreement.
    type: business
  minimum_age:
    text: You must be at least 13 years old to participate in the Network.
    value: '13'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: operate a Device in violation of applicable law, including privacy, data-protection, traffic, or export law
  - summary: Export control representation
    text: you are not located in a country that is subject to a U.S. Government embargo or that has been designated by the U.S. Government as a "terrorist supporting" country
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
name: Hivemapper
provenance_date: '2026-11-09'
provider_name: Hivemapper
provider_slug: hivemapper
slug: hivemapper-eligibility
source_date: '2026-11-09'
source_filename: hivemapper-eligibility.yml
source_heading: Eligibility
source_page: https://hivemapper.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hivemapper\naid: hivemapper\nurl: https://hivemapper.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to participate in the Network. If you are under 18, you represent that\n    you have your parent or guardian's permission to participate\n- type: business\n  text: If you are participating on behalf of a company or organization, you represent that you have authority to\n    bind that entity to this Agreement.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: operate a Device\
  \ in violation of applicable law, including privacy, data-protection, traffic, or export\n    law\n- summary: Export control representation\n  text: you are not located in a country that is subject to a U.S. Government embargo or that has been designated\n    by the U.S. Government as a \"terrorist supporting\" country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to participate in the Network.\n"
source_yaml_url: https://artifacts.apis.io/hivemapper/eligibility/hivemapper-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Hivemapper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Mapping
- Geospatial
- Imagery
- Location
- Street View
- Mobility
- Machine Learning
- Web3
---
