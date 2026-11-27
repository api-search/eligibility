---
api_specs:
- filename: tracetail-io-identification-api-openapi.yml
  format: yaml
  label: tracetail-io Identification API
  slug: tracetail-io-identification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracetail-io/openapi/tracetail-io-identification-api-openapi.yml
- filename: tracetail-io-server-api-api-openapi.yml
  format: yaml
  label: tracetail-io Server API
  slug: tracetail-io-server-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracetail-io/openapi/tracetail-io-server-api-api-openapi.yml
- filename: tracetail-io-service-api-openapi.yml
  format: yaml
  label: tracetail-io Service API
  slug: tracetail-io-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracetail-io/openapi/tracetail-io-service-api-openapi.yml
- filename: tracetail-io-setup-links-api-openapi.yml
  format: yaml
  label: tracetail-io Setup links API
  slug: tracetail-io-setup-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracetail-io/openapi/tracetail-io-setup-links-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you accept these terms for that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or rights-infringing use
    text: break the law or infringe anyone's rights
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
name: tracetail-io
provenance_date: '2026-11-10'
provider_name: tracetail-io
provider_slug: tracetail-io
slug: tracetail-io-eligibility
source_date: '2026-11-10'
source_filename: tracetail-io-eligibility.yml
source_heading: Eligibility
source_page: https://tracetail.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tracetail-io\naid: tracetail-io\nurl: https://tracetail.io/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you accept these terms for that organization.\nrestricted_uses:\n- summary: Unlawful or rights-infringing use\n  text: break the law or infringe anyone's rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tracetail-io/eligibility/tracetail-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from tracetail-io's own page on 2026-11-10.
synthetic: false
tags:
- Browser Fingerprinting
- Privacy
- Analytics
- Device Identification
---
