---
api_specs:
- filename: typeface-audiences-api-openapi.yml
  format: yaml
  label: Typeface Audiences API
  slug: typeface-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-audiences-api-openapi.yml
- filename: typeface-authentication-api-openapi.yml
  format: yaml
  label: Typeface Authentication API
  slug: typeface-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-authentication-api-openapi.yml
- filename: typeface-basic-services-api-openapi.yml
  format: yaml
  label: Typeface Basic Services API
  slug: typeface-basic-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-basic-services-api-openapi.yml
- filename: typeface-brand-kits-api-openapi.yml
  format: yaml
  label: Typeface Brand Kits API
  slug: typeface-brand-kits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-brand-kits-api-openapi.yml
- filename: typeface-content-generation-api-openapi.yml
  format: yaml
  label: Typeface Content Generation API
  slug: typeface-content-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-content-generation-api-openapi.yml
- filename: typeface-content-service-api-openapi.yml
  format: yaml
  label: Typeface Content Service API
  slug: typeface-content-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-content-service-api-openapi.yml
- filename: typeface-digital-assets-api-openapi.yml
  format: yaml
  label: Typeface Digital Assets API
  slug: typeface-digital-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-digital-assets-api-openapi.yml
- filename: typeface-discovery-api-openapi.yml
  format: yaml
  label: Typeface Discovery API
  slug: typeface-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-discovery-api-openapi.yml
- filename: typeface-feeds-api-openapi.yml
  format: yaml
  label: Typeface Feeds API
  slug: typeface-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-feeds-api-openapi.yml
- filename: typeface-profile-service-api-openapi.yml
  format: yaml
  label: Typeface Profile Service API
  slug: typeface-profile-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-profile-service-api-openapi.yml
- filename: typeface-projects-api-openapi.yml
  format: yaml
  label: Typeface Projects API
  slug: typeface-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-projects-api-openapi.yml
- filename: typeface-provisioning-api-openapi.yml
  format: yaml
  label: Typeface Provisioning API
  slug: typeface-provisioning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-provisioning-api-openapi.yml
- filename: typeface-provisioning-service-api-openapi.yml
  format: yaml
  label: Typeface Provisioning Service API
  slug: typeface-provisioning-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-provisioning-service-api-openapi.yml
- filename: typeface-search-service-api-openapi.yml
  format: yaml
  label: Typeface Search Service API
  slug: typeface-search-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-search-service-api-openapi.yml
- filename: typeface-tag-library-api-openapi.yml
  format: yaml
  label: Typeface Tag Library API
  slug: typeface-tag-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typeface/openapi/typeface-tag-library-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Export controls bar use by persons on US sanctions lists and by nationals or residents of countries under US sanctions or embargoes, without naming specific countries.
  entity_types:
  - text: You may use our Service only if you can form a legally binding contract with us
    type: individual
  - text: you represent and warrant that you have the authority to bind that Organization to these Terms
    type: business
  minimum_age:
    text: To use our Service, you must be at least eighteen (18) years of age or, if higher, at least the age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Competitive use of the Service
    text: use or display our Service in competition with us, to develop competing products or services, for benchmarking or competitive analysis of our Service
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
name: Typeface
provenance_date: '2026-11-10'
provider_name: Typeface
provider_slug: typeface
slug: typeface-eligibility
source_date: '2026-11-10'
source_filename: typeface-eligibility.yml
source_heading: Eligibility
source_page: https://www.typeface.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Typeface\naid: typeface\nurl: https://www.typeface.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Export controls bar use by persons on US sanctions lists and by nationals or residents of countries under\n    US sanctions or embargoes, without naming specific countries.\nentity_types:\n- type: individual\n  text: You may use our Service only if you can form a legally binding contract with us\n- type: business\n  text: you represent and warrant that you have the authority to bind that Organization to these Terms\nrestricted_uses:\n- summary: Competitive use of\
  \ the Service\n  text: use or display our Service in competition with us, to develop competing products or services, for benchmarking\n    or competitive analysis of our Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use our Service, you must be at least eighteen (18) years of age or, if higher, at least the age of majority\n    in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/typeface/eligibility/typeface-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Typeface's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Content Generation
- Marketing
- Agents
- Generative AI
- Brand Management
- Enterprise
---
