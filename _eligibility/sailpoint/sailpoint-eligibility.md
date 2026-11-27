---
api_specs:
- filename: sailpoint-access-profiles-api-openapi.yml
  format: yaml
  label: SailPoint Access Profiles API
  slug: sailpoint-access-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sailpoint/openapi/sailpoint-access-profiles-api-openapi.yml
- filename: sailpoint-certifications-api-openapi.yml
  format: yaml
  label: SailPoint Certifications API
  slug: sailpoint-certifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sailpoint/openapi/sailpoint-certifications-api-openapi.yml
- filename: sailpoint-identities-api-openapi.yml
  format: yaml
  label: SailPoint Identities API
  slug: sailpoint-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sailpoint/openapi/sailpoint-identities-api-openapi.yml
- filename: sailpoint-roles-api-openapi.yml
  format: yaml
  label: SailPoint Roles API
  slug: sailpoint-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sailpoint/openapi/sailpoint-roles-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: either you as an individual
    type: individual
  - text: the entity or organization on whose behalf you are entering into these terms and conditions
    type: business
  minimum_age:
    text: YOU HEREBY CERTIFY THAT YOU ARE OF LEGAL AGE TO ENTER INTO THESE TERMS
    value: legal age
  restricted_uses:
  - summary: Competing with SailPoint or benchmarking
    text: accessing the Website for the purpose of competing with SailPoint or using the Website for purposes of benchmarking or other similar purposes
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
name: SailPoint
provenance_date: '2026-11-10'
provider_name: SailPoint
provider_slug: sailpoint
slug: sailpoint-eligibility
source_date: '2026-11-10'
source_filename: sailpoint-eligibility.yml
source_heading: Eligibility
source_page: https://www.sailpoint.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SailPoint\naid: sailpoint\nurl: https://www.sailpoint.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: either you as an individual\n- type: business\n  text: the entity or organization on whose behalf you are entering into these terms and conditions\nrestricted_uses:\n- summary: Competing with SailPoint or benchmarking\n  text: accessing the Website for the purpose of competing with SailPoint or using the Website for purposes of benchmarking\n    or other similar purposes\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: YOU HEREBY CERTIFY THAT YOU ARE OF LEGAL AGE TO ENTER INTO THESE TERMS\n"
source_yaml_url: https://artifacts.apis.io/sailpoint/eligibility/sailpoint-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SailPoint's own page on 2026-11-10.
synthetic: false
tags:
- Access Governance
- Compliance
- Identity and Access Management
- Identity Security
- Security
---
