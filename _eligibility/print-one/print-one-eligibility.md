---
api_specs:
- filename: print-one-address-api-openapi.yml
  format: yaml
  label: print-one Address API
  slug: print-one-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-address-api-openapi.yml
- filename: print-one-campaigns-api-openapi.yml
  format: yaml
  label: print-one Campaigns API
  slug: print-one-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-campaigns-api-openapi.yml
- filename: print-one-coupons-api-openapi.yml
  format: yaml
  label: print-one Coupons API
  slug: print-one-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-coupons-api-openapi.yml
- filename: print-one-design-previews-api-openapi.yml
  format: yaml
  label: print-one Design Previews API
  slug: print-one-design-previews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-design-previews-api-openapi.yml
- filename: print-one-designs-api-openapi.yml
  format: yaml
  label: print-one Designs API
  slug: print-one-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-designs-api-openapi.yml
- filename: print-one-imports-api-openapi.yml
  format: yaml
  label: print-one Imports API
  slug: print-one-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-imports-api-openapi.yml
- filename: print-one-items-api-openapi.yml
  format: yaml
  label: print-one Items API
  slug: print-one-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-items-api-openapi.yml
- filename: print-one-mailings-api-openapi.yml
  format: yaml
  label: print-one Mailings API
  slug: print-one-mailings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-mailings-api-openapi.yml
- filename: print-one-webhooks-api-openapi.yml
  format: yaml
  label: print-one Webhooks API
  slug: print-one-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-webhooks-api-openapi.yml
- filename: print-one-webhook-events-api-openapi.yml
  format: yaml
  label: print-one Webhook Events API
  slug: print-one-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/print-one/openapi/print-one-webhook-events-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Dutch law applies even if the client orders from abroad and/or is domiciled there.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Print.one is entitled, at its own discretion, to carry out an acceptance check with regard to the creditworthiness of the client. Accordingly, Print.one has the right to refuse the client and/or (an) order(s) from the client or to impose further conditions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: print-one
provenance_date: '2026-11-10'
provider_name: print-one
provider_slug: print-one
slug: print-one-eligibility
source_date: '2026-11-10'
source_filename: print-one-eligibility.yml
source_heading: Eligibility
source_page: https://print.one/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: print-one\naid: print-one\nurl: https://print.one/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Dutch law applies even if the client orders from abroad and/or is domiciled there.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Print.one is entitled, at its own discretion, to carry out an acceptance check with regard to the creditworthiness\n    of the client. Accordingly, Print.one has the right to refuse the client and/or (an) order(s) from the client\n    or to impose further conditions.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/print-one/eligibility/print-one-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from print-one's own page on 2026-11-10.
synthetic: false
tags:
- Postcards
- Direct Mail
- Marketing
- Automation
---
