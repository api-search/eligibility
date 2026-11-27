---
api_specs:
- filename: ryft-ingest-api-openapi.yml
  format: yaml
  label: Ryft Ingest API
  slug: ryft-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ryft/openapi/ryft-ingest-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual or an individual accepting these Terms on behalf of a legal entity, that you are at least 18 years old or of sufficient legal age to accept these Terms in accordance with the laws of your jurisdiction
    type: individual
  minimum_age:
    text: at least 18 years old or of sufficient legal age to accept these Terms in accordance with the laws of your jurisdiction
    value: '18'
  restricted_uses:
  - summary: No spam or illegal content
    text: send "spam" or unauthorized commercial communications
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
name: Ryft
provenance_date: '2026-11-10'
provider_name: Ryft
provider_slug: ryft
slug: ryft-eligibility
source_date: '2026-11-10'
source_filename: ryft-eligibility.yml
source_heading: Eligibility
source_page: https://www.ryft.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ryft\naid: ryft\nurl: https://www.ryft.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual or an individual accepting these Terms on behalf of a legal entity, that you are\n    at least 18 years old or of sufficient legal age to accept these Terms in accordance with the laws of your jurisdiction\nrestricted_uses:\n- summary: No spam or illegal content\n  text: send \"spam\" or unauthorized commercial communications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: at least 18 years old or of sufficient legal age to accept these Terms in accordance with the laws of your\n    jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/ryft/eligibility/ryft-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ryft's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Data Lake
- Lakehouse
- Apache Iceberg
- Data Management
- Analytics
- Query Optimization
- Artificial Intelligence
- MCP
---
