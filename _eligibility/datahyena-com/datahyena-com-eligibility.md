---
api_specs:
- filename: datahyena-com-acquisitions-api-openapi.yml
  format: yaml
  label: datahyena-com Acquisitions API
  slug: datahyena-com-acquisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-acquisitions-api-openapi.yml
- filename: datahyena-com-companies-api-openapi.yml
  format: yaml
  label: datahyena-com Companies API
  slug: datahyena-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-companies-api-openapi.yml
- filename: datahyena-com-exec-moves-api-openapi.yml
  format: yaml
  label: datahyena-com Exec Moves API
  slug: datahyena-com-exec-moves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-exec-moves-api-openapi.yml
- filename: datahyena-com-funding-events-api-openapi.yml
  format: yaml
  label: datahyena-com Funding Events API
  slug: datahyena-com-funding-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-funding-events-api-openapi.yml
- filename: datahyena-com-hiring-signals-api-openapi.yml
  format: yaml
  label: datahyena-com Hiring Signals API
  slug: datahyena-com-hiring-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-hiring-signals-api-openapi.yml
- filename: datahyena-com-investors-api-openapi.yml
  format: yaml
  label: datahyena-com Investors API
  slug: datahyena-com-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datahyena-com/openapi/datahyena-com-investors-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, have legal authority to enter into this agreement, and be using the Service for a legitimate business purpose.
    type: individual
  - text: If you’re using Datahyena on behalf of a company, you confirm you have authority to bind that company.
    type: business
  minimum_age:
    text: You must be at least 18
    value: '18'
  restricted_uses:
  - summary: Unlawful or data-protection-violating use
    text: Use the Service for any unlawful purpose, or in violation of any applicable data-protection law
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
name: datahyena-com
provenance_date: '2026-11-09'
provider_name: datahyena-com
provider_slug: datahyena-com
slug: datahyena-com-eligibility
source_date: '2026-11-09'
source_filename: datahyena-com-eligibility.yml
source_heading: Eligibility
source_page: https://datahyena.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: datahyena-com\naid: datahyena-com\nurl: https://datahyena.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, have legal authority to enter into this agreement, and be using the Service for\n    a legitimate business purpose.\n- type: business\n  text: If you’re using Datahyena on behalf of a company, you confirm you have authority to bind that company.\nrestricted_uses:\n- summary: Unlawful or data-protection-violating use\n  text: Use the Service for any unlawful purpose, or in violation of any applicable\
  \ data-protection law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18\n"
source_yaml_url: https://artifacts.apis.io/datahyena-com/eligibility/datahyena-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from datahyena-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Funding
- M&A
- Hiring
---
