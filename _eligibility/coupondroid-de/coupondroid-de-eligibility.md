---
api_specs:
- filename: coupondroid-de-a2a-api-openapi.yml
  format: yaml
  label: Coupondroid Deutschland A2a API
  slug: coupondroid-de-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-de/openapi/coupondroid-de-a2a-api-openapi.yml
- filename: coupondroid-de-auth-md-api-openapi.yml
  format: yaml
  label: Coupondroid Deutschland Auth.md API
  slug: coupondroid-de-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-de/openapi/coupondroid-de-auth-md-api-openapi.yml
- filename: coupondroid-de-llms-txt-api-openapi.yml
  format: yaml
  label: Coupondroid Deutschland Llms.txt API
  slug: coupondroid-de-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-de/openapi/coupondroid-de-llms-txt-api-openapi.yml
- filename: coupondroid-de-mcp-api-openapi.yml
  format: yaml
  label: Coupondroid Deutschland MCP API
  slug: coupondroid-de-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-de/openapi/coupondroid-de-mcp-api-openapi.yml
- filename: coupondroid-de-well-known-api-openapi.yml
  format: yaml
  label: Coupondroid Deutschland .well Known API
  slug: coupondroid-de-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-de/openapi/coupondroid-de-well-known-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Haben Sie als Verbraucherin oder Verbraucher Ihren gewöhnlichen Aufenthalt in Deutschland, können Ihnen dadurch die zwingenden Schutzvorschriften des deutschen Rechts nicht entzogen werden
  entity_types:
  - text: Als Verbraucher können Sie uns außerdem an Ihrem Wohnsitzgericht verklagen (Art. 18 der Verordnung (EU) Nr. 1215/2012, Brüssel Ia).
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Coupondroid Deutschland
provenance_date: '2026-11-09'
provider_name: Coupondroid Deutschland
provider_slug: coupondroid-de
slug: coupondroid-de-eligibility
source_date: '2026-11-09'
source_filename: coupondroid-de-eligibility.yml
source_heading: Eligibility
source_page: https://coupondroid.de/corp/nutzungsbedingungen
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coupondroid Deutschland\naid: coupondroid-de\nurl: https://coupondroid.de/corp/nutzungsbedingungen\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Haben Sie als Verbraucherin oder Verbraucher Ihren gewöhnlichen Aufenthalt in Deutschland, können Ihnen\n    dadurch die zwingenden Schutzvorschriften des deutschen Rechts nicht entzogen werden\nentity_types:\n- type: individual\n  text: Als Verbraucher können Sie uns außerdem an Ihrem Wohnsitzgericht verklagen (Art. 18 der Verordnung (EU)\n    Nr. 1215/2012, Brüssel Ia).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coupondroid-de/eligibility/coupondroid-de-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Coupondroid Deutschland's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Deals
- Discounts
- E-Commerce
- Germany
- Shopping
- Vouchers
---
