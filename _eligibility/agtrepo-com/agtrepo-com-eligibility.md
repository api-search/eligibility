---
api_specs:
- filename: agtrepo-com-account-api-openapi.yml
  format: yaml
  label: A2A Account API
  slug: agtrepo-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-account-api-openapi.yml
- filename: agtrepo-com-auth-api-openapi.yml
  format: yaml
  label: A2A Auth API
  slug: agtrepo-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-auth-api-openapi.yml
- filename: agtrepo-com-billing-api-openapi.yml
  format: yaml
  label: A2A Billing API
  slug: agtrepo-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-billing-api-openapi.yml
- filename: agtrepo-com-discovery-api-openapi.yml
  format: yaml
  label: A2A Discovery API
  slug: agtrepo-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-discovery-api-openapi.yml
- filename: agtrepo-com-feedback-api-openapi.yml
  format: yaml
  label: A2A Feedback API
  slug: agtrepo-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-feedback-api-openapi.yml
- filename: agtrepo-com-key-requests-api-openapi.yml
  format: yaml
  label: A2A Key Requests API
  slug: agtrepo-com-key-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-key-requests-api-openapi.yml
- filename: agtrepo-com-memory-api-openapi.yml
  format: yaml
  label: A2A Memory API
  slug: agtrepo-com-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-memory-api-openapi.yml
- filename: agtrepo-com-search-api-openapi.yml
  format: yaml
  label: A2A Search API
  slug: agtrepo-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not (a) located in, organized under the laws of, or ordinarily resident in any country or territory subject to comprehensive sanctions by the United States, European Union, or United Nations
  entity_types:
  - text: If you are interacting with the Protocol on behalf of an organization, software system, or other principal, you represent that you have the authority to bind that principal
    type: business
  - text: You represent that you (or the natural or legal person you act on behalf of) have the legal capacity to enter into these Terms
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned or restricted persons
    text: listed on any restricted-party or denied-persons list maintained by the U.S. Treasury’s Office of Foreign Assets Control (OFAC) or an equivalent body
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Protocol does not require account registration, usernames, passwords, or stored payment credentials; access is governed entirely by possession of a compatible cryptographic wallet
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: A2A
provenance_date: '2026-11-09'
provider_name: A2A
provider_slug: agtrepo-com
slug: agtrepo-com-eligibility
source_date: '2026-11-09'
source_filename: agtrepo-com-eligibility.yml
source_heading: Eligibility
source_page: https://agtrepo.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A2A\naid: agtrepo-com\nurl: https://agtrepo.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not (a) located in, organized under the laws of, or ordinarily resident in any\n    country or territory subject to comprehensive sanctions by the United States, European Union, or United Nations\nentity_types:\n- type: business\n  text: If you are interacting with the Protocol on behalf of an organization, software system, or other principal,\n    you represent that you have the authority to bind that principal\n- type: individual\n  text: You represent\
  \ that you (or the natural or legal person you act on behalf of) have the legal capacity to\n    enter into these Terms\nrestricted_uses:\n- summary: Sanctioned or restricted persons\n  text: listed on any restricted-party or denied-persons list maintained by the U.S. Treasury’s Office of Foreign\n    Assets Control (OFAC) or an equivalent body\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Protocol does not require account registration, usernames, passwords, or stored payment credentials;\n    access is governed entirely by possession of a compatible cryptographic wallet\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agtrepo-com/eligibility/agtrepo-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from A2A's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Persistent-Memory
- MCP
- Payments
- Encryption
- Storage
---
