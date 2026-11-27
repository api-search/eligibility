---
api_specs:
- filename: renesas-board-kit-api-openapi.yml
  format: yaml
  label: Renesas Board & Kit API
  slug: renesas-board-kit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/renesas/openapi/renesas-board-kit-api-openapi.yml
- filename: renesas-document-api-openapi.yml
  format: yaml
  label: Renesas Document API
  slug: renesas-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/renesas/openapi/renesas-document-api-openapi.yml
- filename: renesas-package-api-openapi.yml
  format: yaml
  label: Renesas Package API
  slug: renesas-package-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/renesas/openapi/renesas-package-api-openapi.yml
- filename: renesas-product-api-openapi.yml
  format: yaml
  label: Renesas Product API
  slug: renesas-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/renesas/openapi/renesas-product-api-openapi.yml
- filename: renesas-product-part-api-openapi.yml
  format: yaml
  label: Renesas Product Part API
  slug: renesas-product-part-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/renesas/openapi/renesas-product-part-api-openapi.yml
- filename: renesas-software-tool-api-openapi.yml
  format: yaml
  label: Renesas Software Tool API
  slug: renesas-software-tool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/renesas/openapi/renesas-software-tool-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - JP
    text: These products and services may only be purchased, obtained and used by persons residing in Japan.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Life-critical or high-risk systems
    text: Renesas Electronics products are not intended or authorized for use in products or systems that may pose a direct threat to human life or bodily injury (artificial life support devices or systems; surgical implantations; etc.), or may cause serious property damage
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
name: Renesas
provenance_date: '2026-11-10'
provider_name: Renesas
provider_slug: renesas
slug: renesas-eligibility
source_date: '2026-11-10'
source_filename: renesas-eligibility.yml
source_heading: Eligibility
source_page: https://www.renesas.com/en/legal-notices
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Renesas\naid: renesas\nurl: https://www.renesas.com/en/legal-notices\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - JP\n  excluded: []\n  text: These products and services may only be purchased, obtained and used by persons residing in Japan.\nentity_types: []\nrestricted_uses:\n- summary: Life-critical or high-risk systems\n  text: Renesas Electronics products are not intended or authorized for use in products or systems that may pose\n    a direct threat to human life or bodily injury (artificial life support devices or systems; surgical implantations;\n    etc.), or may cause serious property damage\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/renesas/eligibility/renesas-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Renesas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Semiconductors
- Microcontrollers
- Electronics
- Hardware
- Product Data
- Automotive
- Industrial
- Embedded
- Developer Tools
---
