---
api_specs:
- filename: sudomock-com-account-api-openapi.yml
  format: yaml
  label: sudomock-com Account API
  slug: sudomock-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-account-api-openapi.yml
- filename: sudomock-com-background-removal-api-openapi.yml
  format: yaml
  label: sudomock-com Background removal API
  slug: sudomock-com-background-removal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-background-removal-api-openapi.yml
- filename: sudomock-com-fonts-api-openapi.yml
  format: yaml
  label: sudomock-com Fonts API
  slug: sudomock-com-fonts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-fonts-api-openapi.yml
- filename: sudomock-com-jobs-api-openapi.yml
  format: yaml
  label: sudomock-com Jobs API
  slug: sudomock-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-jobs-api-openapi.yml
- filename: sudomock-com-photo-mockups-api-openapi.yml
  format: yaml
  label: sudomock-com Photo mockups API
  slug: sudomock-com-photo-mockups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-photo-mockups-api-openapi.yml
- filename: sudomock-com-psd-mockups-api-openapi.yml
  format: yaml
  label: sudomock-com PSD mockups API
  slug: sudomock-com-psd-mockups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-psd-mockups-api-openapi.yml
- filename: sudomock-com-studio-api-openapi.yml
  format: yaml
  label: sudomock-com Studio API
  slug: sudomock-com-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-studio-api-openapi.yml
- filename: sudomock-com-video-mockups-api-openapi.yml
  format: yaml
  label: sudomock-com Video mockups API
  slug: sudomock-com-video-mockups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-video-mockups-api-openapi.yml
- filename: sudomock-com-webhook-deliveries-api-openapi.yml
  format: yaml
  label: sudomock-com Webhook deliveries API
  slug: sudomock-com-webhook-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-webhook-deliveries-api-openapi.yml
- filename: sudomock-com-webhook-endpoints-api-openapi.yml
  format: yaml
  label: sudomock-com Webhook endpoints API
  slug: sudomock-com-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-webhook-endpoints-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Not be located in, or a resident of, any country or region subject to comprehensive U.S. sanctions (currently including Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine)
  entity_types:
  - text: Be at least 18 years old or have parental consent
    type: individual
  minimum_age:
    text: Be at least 18 years old or have parental consent
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: Use the Service for any illegal or unauthorized purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: sudomock-com
provenance_date: '2026-11-10'
provider_name: sudomock-com
provider_slug: sudomock-com
slug: sudomock-com-eligibility
source_date: '2026-11-10'
source_filename: sudomock-com-eligibility.yml
source_heading: Eligibility
source_page: https://sudomock.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sudomock-com\naid: sudomock-com\nurl: https://sudomock.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Not be located in, or a resident of, any country or region subject to comprehensive U.S. sanctions (currently\n    including Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine)\nentity_types:\n- type: individual\n  text: Be at least 18 years old or have parental consent\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Use the Service for any illegal or unauthorized purpose\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old or have parental consent\n"
source_yaml_url: https://artifacts.apis.io/sudomock-com/eligibility/sudomock-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from sudomock-com's own page on 2026-11-10.
synthetic: false
tags:
- Mockup
- PSD
- E-Commerce
- Automation
---
