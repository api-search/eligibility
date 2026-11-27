---
api_specs:
- filename: seekrit-dev-docs-openapi-generated.yml
  format: yaml
  label: seekrit-dev docs API
  slug: docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seekrit-dev/openapi/_ae-authored/seekrit-dev-docs-openapi-generated.yml
- filename: seekrit-dev-guides-openapi-generated.yml
  format: yaml
  label: seekrit-dev guides API
  slug: guides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seekrit-dev/openapi/_ae-authored/seekrit-dev-guides-openapi-generated.yml
- filename: seekrit-dev-reference-openapi-generated.yml
  format: yaml
  label: seekrit-dev reference API
  slug: reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seekrit-dev/openapi/_ae-authored/seekrit-dev-reference-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of legal majority where you live) and able to form a binding contract to use the Service.
    type: individual
  - text: If you create an organization on behalf of a company or other entity, you represent that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of legal majority where you live)
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: you're responsible for complying with any export control or sanctions laws that apply to your use of it.
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
name: seekrit-dev
provenance_date: '2026-11-10'
provider_name: seekrit-dev
provider_slug: seekrit-dev
slug: seekrit-dev-eligibility
source_date: '2026-11-10'
source_filename: seekrit-dev-eligibility.yml
source_heading: Eligibility
source_page: https://seekrit.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: seekrit-dev\naid: seekrit-dev\nurl: https://seekrit.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of legal majority where you live) and able to form a binding\n    contract to use the Service.\n- type: business\n  text: If you create an organization on behalf of a company or other entity, you represent that you have authority\n    to bind that entity to these Terms.\nrestricted_uses:\n- summary: Export control and sanctions\n  text: you're responsible for complying with any\
  \ export control or sanctions laws that apply to your use of it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of legal majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/seekrit-dev/eligibility/seekrit-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from seekrit-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Secrets Management
- Encryption
- Cloudflare
---
