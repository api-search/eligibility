---
api_specs:
- filename: olo-webhooks-asyncapi.yml
  format: yaml
  label: Olo Webhooks
  slug: olo-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/olo/asyncapi/olo-webhooks-asyncapi.yml
- filename: olo-accounts-api-openapi.yml
  format: yaml
  label: Olo Accounts API
  slug: olo-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/olo/openapi/olo-accounts-api-openapi.yml
- filename: olo-accruals-api-openapi.yml
  format: yaml
  label: Olo Accruals API
  slug: olo-accruals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/olo/openapi/olo-accruals-api-openapi.yml
- filename: olo-brand-api-openapi.yml
  format: yaml
  label: Olo Brand API
  slug: olo-brand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/olo/openapi/olo-brand-api-openapi.yml
- filename: olo-promotions-api-openapi.yml
  format: yaml
  label: Olo Promotions API
  slug: olo-promotions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/olo/openapi/olo-promotions-api-openapi.yml
- filename: olo-rails-api-openapi.yml
  format: yaml
  label: Olo Rails API
  slug: olo-rails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/olo/openapi/olo-rails-api-openapi.yml
- filename: olo-users-api-openapi.yml
  format: yaml
  label: Olo Users API
  slug: olo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/olo/openapi/olo-users-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: worldwide (except as limited below)
  entity_types:
  - text: “You” means the individual person accessing or using the Olo APIs on his or her own behalf;
    type: individual
  - text: if the Olo APIs or documentation are accessed or used on behalf of an organization, corporation or other legal entity, “you” means such legal entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Adult content, gambling, tobacco or alcohol
    text: use the Olo APIs in any application that contains or displays adult content, promotes gambling, involves the sale of tobacco or alcohol to persons under 21 years of age, or otherwise violates any law or regulation;
  - summary: Payment data without PCI compliance
    text: 'make requests of any kind to the Olo APIs: (a) with payment data unless the requestor is PCI compliant;'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Credentials for production will only be granted after certification, which must be completed separately for each Olo API.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Olo
provenance_date: '2026-11-10'
provider_name: Olo
provider_slug: olo
slug: olo-eligibility
source_date: '2026-11-10'
source_filename: olo-eligibility.yml
source_heading: Eligibility
source_page: https://www.olo.com/api-usage-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Olo\naid: olo\nurl: https://www.olo.com/api-usage-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: worldwide (except as limited below)\nentity_types:\n- type: individual\n  text: “You” means the individual person accessing or using the Olo APIs on his or her own behalf;\n- type: business\n  text: if the Olo APIs or documentation are accessed or used on behalf of an organization, corporation or other\n    legal entity, “you” means such legal entity.\nrestricted_uses:\n- summary: Adult content, gambling, tobacco or alcohol\n  text: use the Olo APIs in any application that contains\
  \ or displays adult content, promotes gambling, involves\n    the sale of tobacco or alcohol to persons under 21 years of age, or otherwise violates any law or regulation;\n- summary: Payment data without PCI compliance\n  text: 'make requests of any kind to the Olo APIs: (a) with payment data unless the requestor is PCI compliant;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Credentials for production will only be granted after certification, which must be completed separately\n    for each Olo API.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/olo/eligibility/olo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Olo's own page on 2026-11-10.
synthetic: false
tags:
- Food Service
- Restaurant
- Online Ordering
- Delivery
- Point-of-Sale
- Hospitality
- Payments
- Loyalty
- Marketing
---
