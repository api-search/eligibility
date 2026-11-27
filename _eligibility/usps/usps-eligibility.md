---
api_specs:
- filename: usps-addresses-api-openapi.yml
  format: yaml
  label: United States Postal Service Addresses API
  slug: usps-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-addresses-api-openapi.yml
- filename: usps-carrier-pickup-api-openapi.yml
  format: yaml
  label: United States Postal Service Carrier Pickup API
  slug: usps-carrier-pickup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-carrier-pickup-api-openapi.yml
- filename: usps-domestic-prices-api-openapi.yml
  format: yaml
  label: United States Postal Service Domestic Prices API
  slug: usps-domestic-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-domestic-prices-api-openapi.yml
- filename: usps-files-api-openapi.yml
  format: yaml
  label: United States Postal Service Files API
  slug: usps-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-files-api-openapi.yml
- filename: usps-listener-url-specification-api-openapi.yml
  format: yaml
  label: United States Postal Service Listener URL Specification API
  slug: usps-listener-url-specification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-listener-url-specification-api-openapi.yml
- filename: usps-resources-api-openapi.yml
  format: yaml
  label: United States Postal Service Resources API
  slug: usps-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-resources-api-openapi.yml
- filename: usps-tracking-api-openapi.yml
  format: yaml
  label: United States Postal Service Tracking API
  slug: usps-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usps/openapi/usps-tracking-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (the “Individual”)
    type: individual
  - text: the company, entity, or organization that you are representing, if any (the “Company,”
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: you warrant to the Postal Service that You will not use the Service for any purpose that is unlawful or prohibited by these Terms of Use.
  - summary: Use only for USPS transactions
    text: User agrees to only use the USPS Web site, APIs, and USPS data to facilitate USPS shipping or mailing transactions unless specifically allowed otherwise in a specific USPS license.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The Postal Service may use a third-party identity proofing company during the registration process in order to better ensure Your right to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: United States Postal Service
provenance_date: '2026-11-10'
provider_name: United States Postal Service
provider_slug: usps
slug: usps-eligibility
source_date: '2026-11-10'
source_filename: usps-eligibility.yml
source_heading: Eligibility
source_page: https://developers.usps.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: United States Postal Service\naid: usps\nurl: https://developers.usps.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (the “Individual”)\n- type: business\n  text: the company, entity, or organization that you are representing, if any (the “Company,”\nrestricted_uses:\n- summary: Unlawful use\n  text: you warrant to the Postal Service that You will not use the Service for any purpose that is unlawful or\n    prohibited by these Terms of Use.\n- summary: Use only for USPS transactions\n  text: User agrees\
  \ to only use the USPS Web site, APIs, and USPS data to facilitate USPS shipping or mailing transactions\n    unless specifically allowed otherwise in a specific USPS license.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: The Postal Service may use a third-party identity proofing company during the registration process in order\n    to better ensure Your right to use the Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/usps/eligibility/usps-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from United States Postal Service's own page on 2026-11-10.
synthetic: false
tags:
- Government
- Postal Service
- Shipping
- Logistics
- Address Validation
- Package Tracking
---
