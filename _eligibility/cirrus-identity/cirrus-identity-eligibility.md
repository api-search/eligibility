---
api_specs:
- filename: cirrus-identity-endpoints-api-openapi.yml
  format: yaml
  label: Cirrus Identity Endpoints API
  slug: cirrus-identity-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cirrus-identity/openapi/cirrus-identity-endpoints-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual, you are 18 years or older and have full power and authority to agree to these Terms
    type: individual
  - text: Where a contractual agreement (the “Agreement”) exists between an organization (the “Customer”) and Cirrus Identity, the terms and conditions for the Customer’s use of Cirrus Identity services are defined by the Agreement
    type: business
  minimum_age:
    text: you must be at least 18 years old and provide current, complete, truthful, and accurate information
    value: '18'
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: You will not use the Site for any purpose that is unlawful or otherwise in violation of these Terms.
  - summary: Competing use
    text: you are not using the Site for reasons that are in competition with Cirrus Identity.
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
name: Cirrus Identity
provenance_date: '2026-11-09'
provider_name: Cirrus Identity
provider_slug: cirrus-identity
slug: cirrus-identity-eligibility
source_date: '2026-11-09'
source_filename: cirrus-identity-eligibility.yml
source_heading: Eligibility
source_page: https://www.cirrusidentity.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cirrus Identity\naid: cirrus-identity\nurl: https://www.cirrusidentity.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual, you are 18 years or older and have full power and authority to agree to these\n    Terms\n- type: business\n  text: Where a contractual agreement (the “Agreement”) exists between an organization (the “Customer”) and Cirrus\n    Identity, the terms and conditions for the Customer’s use of Cirrus Identity services are defined by the Agreement\nrestricted_uses:\n- summary:\
  \ Unlawful or unauthorized use\n  text: You will not use the Site for any purpose that is unlawful or otherwise in violation of these Terms.\n- summary: Competing use\n  text: you are not using the Site for reasons that are in competition with Cirrus Identity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old and provide current, complete, truthful, and accurate information\n"
source_yaml_url: https://artifacts.apis.io/cirrus-identity/eligibility/cirrus-identity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cirrus Identity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Authentication
- SSO
- SAML
- OpenID Connect
- Higher Education
- Identity and Access Management
- Federation
- Logs
- Identity Federation
---
