---
api_specs:
- filename: fullcontact-address-api-openapi.yml
  format: yaml
  label: FullContact Address API
  slug: fullcontact-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-address-api-openapi.yml
- filename: fullcontact-audience-api-openapi.yml
  format: yaml
  label: FullContact Audience API
  slug: fullcontact-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-audience-api-openapi.yml
- filename: fullcontact-enrich-api-openapi.yml
  format: yaml
  label: FullContact Enrich API
  slug: fullcontact-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-enrich-api-openapi.yml
- filename: fullcontact-identity-api-openapi.yml
  format: yaml
  label: FullContact Identity API
  slug: fullcontact-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-identity-api-openapi.yml
- filename: fullcontact-permission-api-openapi.yml
  format: yaml
  label: FullContact Permission API
  slug: fullcontact-permission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-permission-api-openapi.yml
- filename: fullcontact-tags-api-openapi.yml
  format: yaml
  label: FullContact Tags API
  slug: fullcontact-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fullcontact/openapi/fullcontact-tags-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each Account is for your personal use
    type: individual
  - text: if you represent an entity or other organization, that entity or organization
    type: business
  minimum_age:
    text: The Site, Content, and Services are intended solely for persons who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: permit you to access and use the Site solely for lawful purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Approval of your request to establish an Account will be at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FullContact
provenance_date: '2026-11-09'
provider_name: FullContact
provider_slug: fullcontact
slug: fullcontact-eligibility
source_date: '2026-11-09'
source_filename: fullcontact-eligibility.yml
source_heading: Eligibility
source_page: https://www.fullcontact.com/privacy/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FullContact\naid: fullcontact\nurl: https://www.fullcontact.com/privacy/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each Account is for your personal use\n- type: business\n  text: if you represent an entity or other organization, that entity or organization\nrestricted_uses:\n- summary: Lawful purposes only\n  text: permit you to access and use the Site solely for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Approval of your request to establish an Account will be at\
  \ our sole discretion.\nminimum_age:\n  value: '18'\n  text: The Site, Content, and Services are intended solely for persons who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/fullcontact/eligibility/fullcontact-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from FullContact's own page on 2026-11-09.
synthetic: false
tags:
- Identity Resolution
- Customer Data
- Data Enrichment
- Person API
- Company API
- Privacy-Safe Identity
- Customer Recognition
---
