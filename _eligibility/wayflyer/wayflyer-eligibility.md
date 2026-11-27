---
api_specs:
- filename: wayflyer-auth-api-openapi.yml
  format: yaml
  label: Wayflyer Auth API
  slug: wayflyer-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-auth-api-openapi.yml
- filename: wayflyer-company-details-api-openapi.yml
  format: yaml
  label: Wayflyer Company Details API
  slug: wayflyer-company-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-company-details-api-openapi.yml
- filename: wayflyer-company-search-api-openapi.yml
  format: yaml
  label: Wayflyer Company Search API
  slug: wayflyer-company-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-company-search-api-openapi.yml
- filename: wayflyer-cta-api-openapi.yml
  format: yaml
  label: Wayflyer CTA API
  slug: wayflyer-cta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-cta-api-openapi.yml
- filename: wayflyer-data-upload-api-openapi.yml
  format: yaml
  label: Wayflyer Data Upload API
  slug: wayflyer-data-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-data-upload-api-openapi.yml
- filename: wayflyer-documents-api-openapi.yml
  format: yaml
  label: Wayflyer Documents API
  slug: wayflyer-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-documents-api-openapi.yml
- filename: wayflyer-handover-api-openapi.yml
  format: yaml
  label: Wayflyer Handover API
  slug: wayflyer-handover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-handover-api-openapi.yml
- filename: wayflyer-industry-classification-api-openapi.yml
  format: yaml
  label: Wayflyer Industry Classification API
  slug: wayflyer-industry-classification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-industry-classification-api-openapi.yml
- filename: wayflyer-simulation-api-openapi.yml
  format: yaml
  label: Wayflyer Simulation API
  slug: wayflyer-simulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-simulation-api-openapi.yml
- filename: wayflyer-tracked-login-api-openapi.yml
  format: yaml
  label: Wayflyer Tracked Login API
  slug: wayflyer-tracked-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-tracked-login-api-openapi.yml
- filename: wayflyer-user-details-api-openapi.yml
  format: yaml
  label: Wayflyer User Details API
  slug: wayflyer-user-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayflyer/openapi/wayflyer-user-details-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform and the Services are intended for business use and are not directed towards individual consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal or consumer use
    text: you are not accessing the Platform or using the Services in a personal or consumer capacity;
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
name: Wayflyer
provenance_date: '2026-11-10'
provider_name: Wayflyer
provider_slug: wayflyer
slug: wayflyer-eligibility
source_date: '2026-11-10'
source_filename: wayflyer-eligibility.yml
source_heading: Eligibility
source_page: https://wayflyer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wayflyer\naid: wayflyer\nurl: https://wayflyer.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Platform and the Services are intended for business use and are not directed towards individual consumers.\nrestricted_uses:\n- summary: No personal or consumer use\n  text: you are not accessing the Platform or using the Services in a personal or consumer capacity;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wayflyer/eligibility/wayflyer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Wayflyer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Fintech
- Embedded Finance
- Lending
- Revenue-Based Financing
- Financing
---
