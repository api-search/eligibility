---
api_specs:
- filename: bronjoy-com-api-spec-openapi.json
  format: json
  label: Bronjoy Api-spec API
  slug: bronjoy-api-spec-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bronjoy-com/openapi/_original/bronjoy-com-api-spec-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of a legal entity, you confirm that you are duly authorised to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: use the Service for unlawful, fraudulent, harmful or deceptive purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may register using a verified email address, phone number or Telegram account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bronjoy
provenance_date: '2026-11-09'
provider_name: Bronjoy
provider_slug: bronjoy-com
slug: bronjoy-com-eligibility
source_date: '2026-11-09'
source_filename: bronjoy-com-eligibility.yml
source_heading: Eligibility
source_page: https://bronjoy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bronjoy\naid: bronjoy-com\nurl: https://bronjoy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of a legal entity, you confirm that you are duly authorised to bind\n    that entity to these Terms.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: use the Service for unlawful, fraudulent, harmful or deceptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may register using a verified email address, phone number or Telegram account.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bronjoy-com/eligibility/bronjoy-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Bronjoy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Booking
- Uzbekistan
- Salon
- Healthcare
---
