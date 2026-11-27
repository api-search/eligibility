---
api_specs:
- filename: amazon-ad-groups-api-openapi.yml
  format: yaml
  label: Amazon Ad Groups API
  slug: amazon-ad-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-ad-groups-api-openapi.yml
- filename: amazon-campaigns-api-openapi.yml
  format: yaml
  label: Amazon Campaigns API
  slug: amazon-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-campaigns-api-openapi.yml
- filename: amazon-charge-permissions-api-openapi.yml
  format: yaml
  label: Amazon Charge Permissions API
  slug: amazon-charge-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-charge-permissions-api-openapi.yml
- filename: amazon-charges-api-openapi.yml
  format: yaml
  label: Amazon Charges API
  slug: amazon-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-charges-api-openapi.yml
- filename: amazon-checkout-sessions-api-openapi.yml
  format: yaml
  label: Amazon Checkout Sessions API
  slug: amazon-checkout-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-checkout-sessions-api-openapi.yml
- filename: amazon-keywords-api-openapi.yml
  format: yaml
  label: Amazon Keywords API
  slug: amazon-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-keywords-api-openapi.yml
- filename: amazon-profiles-api-openapi.yml
  format: yaml
  label: Amazon Profiles API
  slug: amazon-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-profiles-api-openapi.yml
- filename: amazon-refunds-api-openapi.yml
  format: yaml
  label: Amazon Refunds API
  slug: amazon-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-refunds-api-openapi.yml
- filename: amazon-reports-api-openapi.yml
  format: yaml
  label: Amazon Ads Reports API
  slug: amazon-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-reports-api-openapi.yml
- filename: amazon-targets-api-openapi.yml
  format: yaml
  label: Amazon Targets API
  slug: amazon-targets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon/openapi/amazon-targets-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (if registering as an individual)
    type: individual
  - text: the entity you represent (if registering as a business)
    type: business
  minimum_age:
    text: You are at least the legal age of majority and that you are able to form a legally binding contract.
    value: legal age of majority
  restricted_uses:
  - summary: Sanctioned parties
    text: You (and all parties that own or control you) are not subject to sanctions or otherwise designated on any list of prohibited or restricted parties maintained by the United States government or other applicable government authority.
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
name: Amazon
provenance_date: '2026-11-09'
provider_name: Amazon
provider_slug: amazon
slug: amazon-eligibility
source_date: '2026-11-09'
source_filename: amazon-eligibility.yml
source_heading: Eligibility
source_page: https://developer.amazon.com/support/legal/da
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon\naid: amazon\nurl: https://developer.amazon.com/support/legal/da\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (if registering as an individual)\n- type: business\n  text: the entity you represent (if registering as a business)\nrestricted_uses:\n- summary: Sanctioned parties\n  text: You (and all parties that own or control you) are not subject to sanctions or otherwise designated on any\n    list of prohibited or restricted parties maintained by the United States government or other applicable government\n\
  \    authority.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age of majority\n  text: You are at least the legal age of majority and that you are able to form a legally binding contract.\n"
source_yaml_url: https://artifacts.apis.io/amazon/eligibility/amazon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Amazon's own page on 2026-11-09.
synthetic: false
tags:
- Amazon
- Advertising
- Alexa
- E-Commerce
- Marketplace
- Payments
- Voice
- Fortune 100
- Agentic Commerce
---
