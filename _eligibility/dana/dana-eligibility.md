---
api_specs:
- filename: dana-availability-api-openapi.yml
  format: yaml
  label: Dana Availability API
  slug: dana-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dana/openapi/dana-availability-api-openapi.yml
- filename: dana-orders-api-openapi.yml
  format: yaml
  label: Dana Orders API
  slug: dana-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dana/openapi/dana-orders-api-openapi.yml
- filename: dana-parts-api-openapi.yml
  format: yaml
  label: Dana Parts API
  slug: dana-parts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dana/openapi/dana-parts-api-openapi.yml
- filename: dana-pricing-api-openapi.yml
  format: yaml
  label: Dana Pricing API
  slug: dana-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dana/openapi/dana-pricing-api-openapi.yml
- filename: dana-shipping-api-openapi.yml
  format: yaml
  label: Dana Shipping API
  slug: dana-shipping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dana/openapi/dana-shipping-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Although the Site is designed for operation within the U.S., we recognize that it may be possible for you to obtain access to the Site from jurisdictions outside the U.S.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law compliance
    text: You may not use or export or re-export any Content or any copy or adaptation of such Content, or any product or service offered on the Site, in violation of any applicable laws or regulations, including without limitation U.S. export laws and regulations.
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
name: Dana
provenance_date: '2026-11-09'
provider_name: Dana
provider_slug: dana
slug: dana-eligibility
source_date: '2026-11-09'
source_filename: dana-eligibility.yml
source_heading: Eligibility
source_page: https://www.dana.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dana\naid: dana\nurl: https://www.dana.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Although the Site is designed for operation within the U.S., we recognize that it may be possible for you\n    to obtain access to the Site from jurisdictions outside the U.S.\nentity_types: []\nrestricted_uses:\n- summary: Export law compliance\n  text: You may not use or export or re-export any Content or any copy or adaptation of such Content, or any product\n    or service offered on the Site, in violation of any applicable laws or regulations, including without limitation\n\
  \    U.S. export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dana/eligibility/dana-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Dana's own page on 2026-11-09.
synthetic: false
tags:
- Aftermarket
- Auto Parts
- Drivetrain
- E-Commerce
- Supply Chain
- Fortune 500
---
