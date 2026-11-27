---
api_specs:
- filename: everframe-dev-openapi-generated.yml
  format: yaml
  label: Everframe API
  slug: everframe-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everframe-dev/openapi/_ae-authored/everframe-dev-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of an organisation, you represent that you are authorised to bind it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive personal data without basis
    text: use the Service to collect sensitive personal data from end users without a lawful basis and appropriate notice and consent
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
name: Everframe
provenance_date: '2026-11-09'
provider_name: Everframe
provider_slug: everframe-dev
slug: everframe-dev-eligibility
source_date: '2026-11-09'
source_filename: everframe-dev-eligibility.yml
source_heading: Eligibility
source_page: https://everframe.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everframe\naid: everframe-dev\nurl: https://everframe.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of an organisation, you represent that you are authorised to bind it.\nrestricted_uses:\n- summary: Sensitive personal data without basis\n  text: use the Service to collect sensitive personal data from end users without a lawful basis and appropriate\n    notice and consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/everframe-dev/eligibility/everframe-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Everframe's own page on 2026-11-09.
synthetic: false
tags:
- Bug Reporting
- SDK
- Mobile
- Web
- TV
---
