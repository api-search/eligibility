---
api_specs:
- filename: signnow-authentication-api-openapi.yml
  format: yaml
  label: SignNow Authentication API
  slug: signnow-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-authentication-api-openapi.yml
- filename: signnow-documents-api-openapi.yml
  format: yaml
  label: SignNow Documents API
  slug: signnow-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-documents-api-openapi.yml
- filename: signnow-envelopes-api-openapi.yml
  format: yaml
  label: SignNow Envelopes API
  slug: signnow-envelopes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-envelopes-api-openapi.yml
- filename: signnow-signing-api-openapi.yml
  format: yaml
  label: SignNow Signing API
  slug: signnow-signing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-signing-api-openapi.yml
- filename: signnow-templates-api-openapi.yml
  format: yaml
  label: SignNow Templates API
  slug: signnow-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-templates-api-openapi.yml
- filename: signnow-users-api-openapi.yml
  format: yaml
  label: SignNow Users API
  slug: signnow-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-users-api-openapi.yml
- filename: signnow-webhooks-api-openapi.yml
  format: yaml
  label: SignNow Webhooks API
  slug: signnow-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signnow/openapi/signnow-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization, the term "you" refers to such organization.
    type: business
  minimum_age:
    text: Our Services are not designed for or marketed to children under 18.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You will comply with all applicable federal laws, regulations, and rules, and complete all required undertakings (including obtaining any necessary export license or other governmental approval), that prohibit or restrict the export or re-export of the Services or any of Your Content outside the United States of America.
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
name: SignNow
provenance_date: '2026-11-10'
provider_name: SignNow
provider_slug: signnow
slug: signnow-eligibility
source_date: '2026-11-10'
source_filename: signnow-eligibility.yml
source_heading: Eligibility
source_page: https://legal.signnow.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SignNow\naid: signnow\nurl: https://legal.signnow.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, the term \"you\" refers to such organization.\nrestricted_uses:\n- summary: Export restrictions\n  text: You will comply with all applicable federal laws, regulations, and rules, and complete all required undertakings\n    (including obtaining any necessary export license or other governmental approval), that prohibit or restrict\n    the export or re-export of the Services\
  \ or any of Your Content outside the United States of America.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are not designed for or marketed to children under 18.\n"
source_yaml_url: https://artifacts.apis.io/signnow/eligibility/signnow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SignNow's own page on 2026-11-10.
synthetic: false
tags:
- E-Signature
- Document Management
- Workflow Automation
---
