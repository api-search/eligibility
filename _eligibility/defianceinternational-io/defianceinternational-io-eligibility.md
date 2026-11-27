---
api_specs:
- filename: defianceinternational-io-catalog-api-openapi.yml
  format: yaml
  label: Defiance International Catalog API
  slug: defianceinternational-io-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defianceinternational-io/openapi/defianceinternational-io-catalog-api-openapi.yml
- filename: defianceinternational-io-content-api-openapi.yml
  format: yaml
  label: Defiance International Content API
  slug: defianceinternational-io-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defianceinternational-io/openapi/defianceinternational-io-content-api-openapi.yml
- filename: defianceinternational-io-documents-api-openapi.yml
  format: yaml
  label: Defiance International Documents API
  slug: defianceinternational-io-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defianceinternational-io/openapi/defianceinternational-io-documents-api-openapi.yml
- filename: defianceinternational-io-machine-documents-api-openapi.yml
  format: yaml
  label: Defiance International Machine Documents API
  slug: defianceinternational-io-machine-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defianceinternational-io/openapi/defianceinternational-io-machine-documents-api-openapi.yml
- filename: defianceinternational-io-platform-api-openapi.yml
  format: yaml
  label: Defiance International Platform API
  slug: defianceinternational-io-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defianceinternational-io/openapi/defianceinternational-io-platform-api-openapi.yml
- filename: defianceinternational-io-research-register-api-openapi.yml
  format: yaml
  label: Defiance International Research Register API
  slug: defianceinternational-io-research-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defianceinternational-io/openapi/defianceinternational-io-research-register-api-openapi.yml
- filename: defianceinternational-io-studies-api-openapi.yml
  format: yaml
  label: Defiance International Studies API
  slug: defianceinternational-io-studies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defianceinternational-io/openapi/defianceinternational-io-studies-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our standard storefront accepts delivery orders only for the 50 United States and the District of Columbia.
  entity_types:
  - text: An individual purchasing on their own behalf is the Buyer and must independently satisfy the research-use requirements.
    type: individual
  - text: If you act for an organization, you must identify it accurately and have authority to bind it.
    type: business
  - text: If you act for a government body, identify known limits on contracting authority before acceptance.
    type: government
  minimum_age:
    text: You must be at least 21 and have reached the age and legal capacity required to enter the agreement where you are located.
    value: '21'
  restricted_uses:
  - summary: Clinical and diagnostic use
    text: Clinical investigation and diagnostic use remain prohibited, including use on human specimens for clinical diagnostic evaluation or patient-care decisions.
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
name: Defiance International
provenance_date: '2026-11-09'
provider_name: Defiance International
provider_slug: defianceinternational-io
slug: defianceinternational-io-eligibility
source_date: '2026-11-09'
source_filename: defianceinternational-io-eligibility.yml
source_heading: Eligibility
source_page: https://defianceinternational.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Defiance International\naid: defianceinternational-io\nurl: https://defianceinternational.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our standard storefront accepts delivery orders only for the 50 United States and the District of Columbia.\nentity_types:\n- type: individual\n  text: An individual purchasing on their own behalf is the Buyer and must independently satisfy the research-use\n    requirements.\n- type: business\n  text: If you act for an organization, you must identify it accurately and have authority to bind it.\n- type: government\n\
  \  text: If you act for a government body, identify known limits on contracting authority before acceptance.\nrestricted_uses:\n- summary: Clinical and diagnostic use\n  text: Clinical investigation and diagnostic use remain prohibited, including use on human specimens for clinical\n    diagnostic evaluation or patient-care decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: You must be at least 21 and have reached the age and legal capacity required to enter the agreement where\n    you are located.\n"
source_yaml_url: https://artifacts.apis.io/defianceinternational-io/eligibility/defianceinternational-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Defiance International's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Research Chemicals
- Peptides
- Certificate of Analysis
- Laboratory Supplies
- E-Commerce
- MCP
---
