---
api_specs:
- filename: e2a-dev-api-openapi.yml
  format: yaml
  label: e2a API API
  slug: e2a-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2a-dev/openapi/_original/e2a-dev-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You confirm you are not on a US or EU sanctions list and will not use the hosted services from or for a sanctioned country or person.
  entity_types:
  - text: If you are using it on behalf of an organization, you confirm you have the authority to bind that organization to these terms.
    type: individual
  - text: If you use the hosted services on behalf of a business or organization, you will defend and indemnify Mnexa against third-party claims
    type: business
  minimum_age:
    text: You must be 13 or older to use Token Canopy.
    value: '13'
  restricted_uses:
  - summary: Spam and phishing
    text: Send spam or phishing, distribute malware, or attack other systems.
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
name: e2a-dev
provenance_date: '2026-11-09'
provider_name: e2a-dev
provider_slug: e2a-dev
slug: e2a-dev-eligibility
source_date: '2026-11-09'
source_filename: e2a-dev-eligibility.yml
source_heading: Eligibility
source_page: https://tokencanopy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: e2a-dev\naid: e2a-dev\nurl: https://tokencanopy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You confirm you are not on a US or EU sanctions list and will not use the hosted services from or for a\n    sanctioned country or person.\nentity_types:\n- type: individual\n  text: If you are using it on behalf of an organization, you confirm you have the authority to bind that organization\n    to these terms.\n- type: business\n  text: If you use the hosted services on behalf of a business or organization, you will defend and indemnify Mnexa\n    against third-party claims\n\
  restricted_uses:\n- summary: Spam and phishing\n  text: Send spam or phishing, distribute malware, or attack other systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 or older to use Token Canopy.\n"
source_yaml_url: https://artifacts.apis.io/e2a-dev/eligibility/e2a-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from e2a-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Open Source
- Artificial Intelligence
---
