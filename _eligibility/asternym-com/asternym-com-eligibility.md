---
api_specs:
- filename: asternym-com-bazi-api-openapi.yml
  format: yaml
  label: AsterNym Bazi API
  slug: asternym-com-bazi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asternym-com/openapi/asternym-com-bazi-api-openapi.yml
- filename: asternym-com-natal-api-openapi.yml
  format: yaml
  label: AsterNym Natal API
  slug: asternym-com-natal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asternym-com/openapi/asternym-com-natal-api-openapi.yml
- filename: asternym-com-numerology-api-openapi.yml
  format: yaml
  label: AsterNym Numerology API
  slug: asternym-com-numerology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asternym-com/openapi/asternym-com-numerology-api-openapi.yml
- filename: asternym-com-reading-api-openapi.yml
  format: yaml
  label: AsterNym Reading API
  slug: asternym-com-reading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asternym-com/openapi/asternym-com-reading-api-openapi.yml
- filename: asternym-com-zodiac-api-openapi.yml
  format: yaml
  label: AsterNym Zodiac API
  slug: asternym-com-zodiac-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asternym-com/openapi/asternym-com-zodiac-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Operated by Moat Ventures, located in Hong Kong. No served or excluded country list is stated for the service.
  entity_types:
  - text: You must be 18 or older to create an account or make a purchase.
    type: individual
  minimum_age:
    text: You must be 18 or older to create an account or make a purchase.
    value: '18'
  restricted_uses:
  - summary: No medical, legal, financial or safety decisions
    text: Nothing on AsterNym should be used as the basis for a medical, psychological, legal, financial or safety decision.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An account requires an email address. AsterNym sends a one-time code to that address to verify access and begin a session.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AsterNym
provenance_date: '2026-11-09'
provider_name: AsterNym
provider_slug: asternym-com
slug: asternym-com-eligibility
source_date: '2026-11-09'
source_filename: asternym-com-eligibility.yml
source_heading: Eligibility
source_page: https://asternym.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AsterNym\naid: asternym-com\nurl: https://asternym.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Operated by Moat Ventures, located in Hong Kong. No served or excluded country list is stated for the service.\nentity_types:\n- type: individual\n  text: You must be 18 or older to create an account or make a purchase.\nrestricted_uses:\n- summary: No medical, legal, financial or safety decisions\n  text: Nothing on AsterNym should be used as the basis for a medical, psychological, legal, financial or safety\n    decision.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: An account requires an email address. AsterNym sends a one-time code to that address to verify access and\n    begin a session.\nminimum_age:\n  value: '18'\n  text: You must be 18 or older to create an account or make a purchase.\n"
source_yaml_url: https://artifacts.apis.io/asternym-com/eligibility/asternym-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AsterNym's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- BaZi
- Numerology
- Compatibility
- BirthChart
---
