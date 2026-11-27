---
api_specs:
- filename: stannp-account-api-openapi.yml
  format: yaml
  label: Stannp Account API
  slug: stannp-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-account-api-openapi.yml
- filename: stannp-campaigns-api-openapi.yml
  format: yaml
  label: Stannp Campaigns API
  slug: stannp-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-campaigns-api-openapi.yml
- filename: stannp-events-api-openapi.yml
  format: yaml
  label: Stannp Events API
  slug: stannp-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-events-api-openapi.yml
- filename: stannp-groups-api-openapi.yml
  format: yaml
  label: Stannp Groups API
  slug: stannp-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-groups-api-openapi.yml
- filename: stannp-letters-api-openapi.yml
  format: yaml
  label: Stannp Letters API
  slug: stannp-letters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-letters-api-openapi.yml
- filename: stannp-postcards-api-openapi.yml
  format: yaml
  label: Stannp Postcards API
  slug: stannp-postcards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-postcards-api-openapi.yml
- filename: stannp-recipients-api-openapi.yml
  format: yaml
  label: Stannp Recipients API
  slug: stannp-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-recipients-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your right to access and use the Platform to receive the Service is solely for the business purposes of the entity on whose behalf you are authorized to use the Service
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: Is defamatory, obscene, indecent, abusive, offensive, harassing, violent, hateful, inflammatory, or otherwise objectionable
  - summary: Marketing to children under 13
    text: Customers must not use the Service for marketing directed at children under 13 years of age or other vulnerable consumer groups.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All users are required to create an account to access the Platform and the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Stannp
provenance_date: '2026-11-10'
provider_name: Stannp
provider_slug: stannp
slug: stannp-eligibility
source_date: '2026-11-10'
source_filename: stannp-eligibility.yml
source_heading: Eligibility
source_page: https://www.stannp.com/us/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stannp\naid: stannp\nurl: https://www.stannp.com/us/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Your right to access and use the Platform to receive the Service is solely for the business purposes of\n    the entity on whose behalf you are authorized to use the Service\nrestricted_uses:\n- summary: Prohibited content\n  text: Is defamatory, obscene, indecent, abusive, offensive, harassing, violent, hateful, inflammatory, or otherwise\n    objectionable\n- summary: Marketing to children under 13\n\
  \  text: Customers must not use the Service for marketing directed at children under 13 years of age or other vulnerable\n    consumer groups.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All users are required to create an account to access the Platform and the Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stannp/eligibility/stannp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Stannp's own page on 2026-11-10.
synthetic: false
tags:
- Direct Mail
- Postcards
- Letters
- Print
- Physical Mail
- Marketing Automation
- Campaigns
- Address Verification
- SMS
- Webhook
- Mailing Lists
- Fulfillment
---
