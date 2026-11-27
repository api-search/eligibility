---
api_specs:
- filename: cofactr-batch-api-openapi.yml
  format: yaml
  label: Cofactr Batch API
  slug: cofactr-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cofactr/openapi/cofactr-batch-api-openapi.yml
- filename: cofactr-products-api-openapi.yml
  format: yaml
  label: Cofactr Products API
  slug: cofactr-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cofactr/openapi/cofactr-products-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Cofactr makes no representation that the Services are appropriate or available for use in jurisdictions outside the United States. Access to the Services from jurisdictions where such access is illegal is prohibited.
  entity_types:
  - text: If You are entering these Terms not as an individual but on behalf of Your company or other entity for which You are acting, “You” means Your entity and You are binding Your company or entity to these Terms.
    type: business
  minimum_age:
    text: You affirm that You are at least eighteen (18) years of age, or an emancipated minor
    value: '18'
  restricted_uses:
  - summary: Reselling via the Services
    text: You are prohibited from using the Services on behalf of a third party for reselling purposes unless You have entered into an Enterprise Partnership Agreement with Cofactr.
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
name: Cofactr
provenance_date: '2026-11-09'
provider_name: Cofactr
provider_slug: cofactr
slug: cofactr-eligibility
source_date: '2026-11-09'
source_filename: cofactr-eligibility.yml
source_heading: Eligibility
source_page: https://www.cofactr.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cofactr\naid: cofactr\nurl: https://www.cofactr.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Cofactr makes no representation that the Services are appropriate or available for use in jurisdictions\n    outside the United States. Access to the Services from jurisdictions where such access is illegal is prohibited.\nentity_types:\n- type: business\n  text: If You are entering these Terms not as an individual but on behalf of Your company or other entity for which\n    You are acting, “You” means Your entity and You are binding Your company or entity to these\
  \ Terms.\nrestricted_uses:\n- summary: Reselling via the Services\n  text: You are prohibited from using the Services on behalf of a third party for reselling purposes unless You\n    have entered into an Enterprise Partnership Agreement with Cofactr.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that You are at least eighteen (18) years of age, or an emancipated minor\n"
source_yaml_url: https://artifacts.apis.io/cofactr/eligibility/cofactr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cofactr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Physical AI
- Component Intelligence
- Electronics
- Supply Chain
- Procurement
- Manufacturing
- Hardware
- Bill of Materials
---
