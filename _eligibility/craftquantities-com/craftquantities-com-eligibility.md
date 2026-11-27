---
api_specs:
- filename: craftquantities-com-agent-tools-api-openapi.yml
  format: yaml
  label: Craft Quantities Agent tools API
  slug: craftquantities-com-agent-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-agent-tools-api-openapi.yml
- filename: craftquantities-com-benchmark-api-openapi.yml
  format: yaml
  label: Craft Quantities Benchmark API
  slug: craftquantities-com-benchmark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-benchmark-api-openapi.yml
- filename: craftquantities-com-calculators-api-openapi.yml
  format: yaml
  label: Craft Quantities Calculators API
  slug: craftquantities-com-calculators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-calculators-api-openapi.yml
- filename: craftquantities-com-cutting-api-openapi.yml
  format: yaml
  label: Craft Quantities Cutting API
  slug: craftquantities-com-cutting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-cutting-api-openapi.yml
- filename: craftquantities-com-diagnoses-and-documents-api-openapi.yml
  format: yaml
  label: Craft Quantities Diagnoses and documents API
  slug: craftquantities-com-diagnoses-and-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-diagnoses-and-documents-api-openapi.yml
- filename: craftquantities-com-discovery-api-openapi.yml
  format: yaml
  label: Craft Quantities Discovery API
  slug: craftquantities-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-discovery-api-openapi.yml
- filename: craftquantities-com-house-and-canvas-api-openapi.yml
  format: yaml
  label: Craft Quantities House and canvas API
  slug: craftquantities-com-house-and-canvas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-house-and-canvas-api-openapi.yml
- filename: craftquantities-com-planner-api-openapi.yml
  format: yaml
  label: Craft Quantities Planner API
  slug: craftquantities-com-planner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-planner-api-openapi.yml
- filename: craftquantities-com-project-files-api-openapi.yml
  format: yaml
  label: Craft Quantities Project files API
  slug: craftquantities-com-project-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-project-files-api-openapi.yml
- filename: craftquantities-com-quotes-api-openapi.yml
  format: yaml
  label: Craft Quantities Quotes API
  slug: craftquantities-com-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-quotes-api-openapi.yml
- filename: craftquantities-com-solve-backwards-api-openapi.yml
  format: yaml
  label: Craft Quantities Solve backwards API
  slug: craftquantities-com-solve-backwards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-solve-backwards-api-openapi.yml
- filename: craftquantities-com-takeoffs-api-openapi.yml
  format: yaml
  label: Craft Quantities Takeoffs API
  slug: craftquantities-com-takeoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-takeoffs-api-openapi.yml
- filename: craftquantities-com-units-api-openapi.yml
  format: yaml
  label: Craft Quantities Units API
  slug: craftquantities-com-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-units-api-openapi.yml
- filename: craftquantities-com-worked-examples-api-openapi.yml
  format: yaml
  label: Craft Quantities Worked examples API
  slug: craftquantities-com-worked-examples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craftquantities-com/openapi/craftquantities-com-worked-examples-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for personal or commercial work, including in documents you produce for clients
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Presenting output as certified engineering
    text: misrepresent its output as certified engineering
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
name: Craft Quantities
provenance_date: '2026-11-09'
provider_name: Craft Quantities
provider_slug: craftquantities-com
slug: craftquantities-com-eligibility
source_date: '2026-11-09'
source_filename: craftquantities-com-eligibility.yml
source_heading: Eligibility
source_page: https://craftquantities.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Craft Quantities\naid: craftquantities-com\nurl: https://craftquantities.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for personal or commercial work, including in documents you produce for clients\nrestricted_uses:\n- summary: Presenting output as certified engineering\n  text: misrepresent its output as certified engineering\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/craftquantities-com/eligibility/craftquantities-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Craft Quantities's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Calculators
- Estimating
- Building Materials
- Open Data
- MCP
---
