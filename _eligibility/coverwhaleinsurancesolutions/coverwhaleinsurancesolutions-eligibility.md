---
api_specs:
- filename: coverwhaleinsurancesolutions-authentication-api-openapi.yml
  format: yaml
  label: Cover Whale Authentication API
  slug: coverwhaleinsurancesolutions-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coverwhaleinsurancesolutions/openapi/coverwhaleinsurancesolutions-authentication-api-openapi.yml
- filename: coverwhaleinsurancesolutions-binding-api-openapi.yml
  format: yaml
  label: Cover Whale Binding API
  slug: coverwhaleinsurancesolutions-binding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coverwhaleinsurancesolutions/openapi/coverwhaleinsurancesolutions-binding-api-openapi.yml
- filename: coverwhaleinsurancesolutions-policy-lifecycle-api-openapi.yml
  format: yaml
  label: Cover Whale Policy Lifecycle API
  slug: coverwhaleinsurancesolutions-policy-lifecycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coverwhaleinsurancesolutions/openapi/coverwhaleinsurancesolutions-policy-lifecycle-api-openapi.yml
- filename: coverwhaleinsurancesolutions-quoting-api-openapi.yml
  format: yaml
  label: Cover Whale Quoting API
  slug: coverwhaleinsurancesolutions-quoting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coverwhaleinsurancesolutions/openapi/coverwhaleinsurancesolutions-quoting-api-openapi.yml
- filename: coverwhaleinsurancesolutions-reference-data-api-openapi.yml
  format: yaml
  label: Cover Whale Reference Data API
  slug: coverwhaleinsurancesolutions-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coverwhaleinsurancesolutions/openapi/coverwhaleinsurancesolutions-reference-data-api-openapi.yml
- filename: coverwhaleinsurancesolutions-submission-data-api-openapi.yml
  format: yaml
  label: Cover Whale Submission Data API
  slug: coverwhaleinsurancesolutions-submission-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coverwhaleinsurancesolutions/openapi/coverwhaleinsurancesolutions-submission-data-api-openapi.yml
- filename: coverwhaleinsurancesolutions-submissions-api-openapi.yml
  format: yaml
  label: Cover Whale Submissions API
  slug: coverwhaleinsurancesolutions-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coverwhaleinsurancesolutions/openapi/coverwhaleinsurancesolutions-submissions-api-openapi.yml
- filename: coverwhaleinsurancesolutions-webhooks-api-openapi.yml
  format: yaml
  label: Cover Whale Webhooks API
  slug: coverwhaleinsurancesolutions-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coverwhaleinsurancesolutions/openapi/coverwhaleinsurancesolutions-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: It can be accessed from all 50 states and the District of Columbia, as well as from other countries around the world.
  entity_types:
  - text: If you are registering for or using the Service on behalf of a group, company, entity, or organization (a "Subscribing Organization"), you represent and warrant that you are the Subscribing Organization's authorized representative
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: Use the Service for any illegal, unethical, fraudulent, misleading, or objectionable purpose or in breach of any law, regulation, or agreement.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: If your application is approved, you will be required to pay the quoted Third Party Insurance Policy purchase price.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cover Whale
provenance_date: '2026-11-09'
provider_name: Cover Whale
provider_slug: coverwhaleinsurancesolutions
slug: coverwhaleinsurancesolutions-eligibility
source_date: '2026-11-09'
source_filename: coverwhaleinsurancesolutions-eligibility.yml
source_heading: Eligibility
source_page: https://coverwhale.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cover Whale\naid: coverwhaleinsurancesolutions\nurl: https://coverwhale.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: It can be accessed from all 50 states and the District of Columbia, as well as from other countries around\n    the world.\nentity_types:\n- type: business\n  text: If you are registering for or using the Service on behalf of a group, company, entity, or organization (a\n    \"Subscribing Organization\"), you represent and warrant that you are the Subscribing Organization's authorized\n    representative\nrestricted_uses:\n- summary: Illegal or fraudulent\
  \ use\n  text: Use the Service for any illegal, unethical, fraudulent, misleading, or objectionable purpose or in breach\n    of any law, regulation, or agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: If your application is approved, you will be required to pay the quoted Third Party Insurance Policy purchase\n    price.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coverwhaleinsurancesolutions/eligibility/coverwhaleinsurancesolutions-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Cover Whale's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Commercial Auto Insurance
- Insurtech
- Underwriting
- Telematics
- Risk Management
- Fleet Safety
- Policy Lifecycle
- Webhook
- Company
---
