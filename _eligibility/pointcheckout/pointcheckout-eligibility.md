---
api_specs:
- filename: pointcheckout-branches-api-openapi.yml
  format: yaml
  label: PointCheckout Branches API
  slug: pointcheckout-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-branches-api-openapi.yml
- filename: pointcheckout-checkout-api-openapi.yml
  format: yaml
  label: PointCheckout Checkout API
  slug: pointcheckout-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-checkout-api-openapi.yml
- filename: pointcheckout-customer-subscription-api-openapi.yml
  format: yaml
  label: PointCheckout Customer subscription API
  slug: pointcheckout-customer-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-customer-subscription-api-openapi.yml
- filename: pointcheckout-webhooks-api-openapi.yml
  format: yaml
  label: PointCheckout Webhooks API
  slug: pointcheckout-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: PointCheckout Payments is only made available to persons in PointCheckout territories that operate a business selling goods and services.
  entity_types:
  - text: You may register as an individual (sole proprietor)
    type: individual
  - text: or as a corporation or other legal entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No non-commercial use
    text: You may not use the Payments Services for non-commercial, personal, family, or household purposes.
  - summary: Prohibited businesses
    text: The following categories of businesses and business practices are prohibited from using the Payments Services
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
name: PointCheckout
provenance_date: '2026-11-10'
provider_name: PointCheckout
provider_slug: pointcheckout
slug: pointcheckout-eligibility
source_date: '2026-11-10'
source_filename: pointcheckout-eligibility.yml
source_heading: Eligibility
source_page: https://www.pointcheckout.com/en/legal/merchant/merchant-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PointCheckout\naid: pointcheckout\nurl: https://www.pointcheckout.com/en/legal/merchant/merchant-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: PointCheckout Payments is only made available to persons in PointCheckout territories that operate a business\n    selling goods and services.\nentity_types:\n- type: individual\n  text: You may register as an individual (sole proprietor)\n- type: business\n  text: or as a corporation or other legal entity.\nrestricted_uses:\n- summary: No non-commercial use\n  text: You may not use the Payments Services for non-commercial,\
  \ personal, family, or household purposes.\n- summary: Prohibited businesses\n  text: The following categories of businesses and business practices are prohibited from using the Payments Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pointcheckout/eligibility/pointcheckout-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from PointCheckout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Checkout
- Subscription
- Rewards
- Loyalty
- Webhook
- MENA
- E-Commerce
---
