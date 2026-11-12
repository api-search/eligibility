---
api_specs:
- filename: copyright01-com-api-keys-api-openapi.yml
  format: yaml
  label: Copyright01 Api Keys API
  slug: copyright01-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-api-keys-api-openapi.yml
- filename: copyright01-com-deposits-api-openapi.yml
  format: yaml
  label: Copyright01 Deposits API
  slug: copyright01-com-deposits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-deposits-api-openapi.yml
- filename: copyright01-com-me-api-openapi.yml
  format: yaml
  label: Copyright01 Me API
  slug: copyright01-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-me-api-openapi.yml
- filename: copyright01-com-verify-api-openapi.yml
  format: yaml
  label: Copyright01 Verify API
  slug: copyright01-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-verify-api-openapi.yml
- filename: copyright01-com-verify-hash-api-openapi.yml
  format: yaml
  label: Copyright01 Verify Hash API
  slug: copyright01-com-verify-hash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-verify-hash-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Registration is free and open to any individual or legal entity.
    type: individual
  - text: Registration is free and open to any individual or legal entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing deposits
    text: undertake not to deposit any unlawful, infringing, or third-party rights-violating content.
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
name: Copyright01
provenance_date: '2026-11-09'
provider_name: Copyright01
provider_slug: copyright01-com
slug: copyright01-com-eligibility
source_date: '2026-11-09'
source_filename: copyright01-com-eligibility.yml
source_heading: Eligibility
source_page: https://copyright01.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Copyright01\naid: copyright01-com\nurl: https://copyright01.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Registration is free and open to any individual or legal entity.\n- type: business\n  text: Registration is free and open to any individual or legal entity.\nrestricted_uses:\n- summary: Unlawful or infringing deposits\n  text: undertake not to deposit any unlawful, infringing, or third-party rights-violating content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/copyright01-com/eligibility/copyright01-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Copyright01's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Copyright
- Intellectual Property
- Timestamping
- Proof Of Authorship
- Certificates
- MCP
- REST API
---
