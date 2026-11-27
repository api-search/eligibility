---
api_specs:
- filename: wunderkind-email-api-openapi.yml
  format: yaml
  label: Wunderkind Email API
  slug: wunderkind-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-email-api-openapi.yml
- filename: wunderkind-id-resolution-api-openapi.yml
  format: yaml
  label: Wunderkind Id Resolution API
  slug: wunderkind-id-resolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-id-resolution-api-openapi.yml
- filename: wunderkind-identity-api-openapi.yml
  format: yaml
  label: Wunderkind Identity API
  slug: wunderkind-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-identity-api-openapi.yml
- filename: wunderkind-send-event-api-openapi.yml
  format: yaml
  label: Wunderkind Send Event API
  slug: wunderkind-send-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-send-event-api-openapi.yml
- filename: wunderkind-ucrm-api-openapi.yml
  format: yaml
  label: Wunderkind Ucrm API
  slug: wunderkind-ucrm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-ucrm-api-openapi.yml
- filename: wunderkind-wunderhook-api-openapi.yml
  format: yaml
  label: Wunderkind Wunderhook API
  slug: wunderkind-wunderhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wunderkind/openapi/wunderkind-wunderhook-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 18, you may use this Site only with involvement of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Submitted content must not harass or infringe
    text: must not harass, slander, malign, libel, defame, threaten, or otherwise violate any rights of any third-parties
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
name: Wunderkind
provenance_date: '2026-11-10'
provider_name: Wunderkind
provider_slug: wunderkind
slug: wunderkind-eligibility
source_date: '2026-11-10'
source_filename: wunderkind-eligibility.yml
source_heading: Eligibility
source_page: https://www.wunderkind.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wunderkind\naid: wunderkind\nurl: https://www.wunderkind.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Submitted content must not harass or infringe\n  text: must not harass, slander, malign, libel, defame, threaten, or otherwise violate any rights of any third-parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18, you may use this Site only with involvement of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/wunderkind/eligibility/wunderkind-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Wunderkind's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Personalization
- Identity Resolution
- Email
- SMS
- Behavioral Data
- E-Commerce
- Webhook
- Artificial Intelligence
- Identity
---
