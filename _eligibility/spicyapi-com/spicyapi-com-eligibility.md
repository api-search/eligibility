---
api_specs:
- filename: spicyapi-com-agent-tools-api-openapi.yml
  format: yaml
  label: spicyapi-com Agent tools API
  slug: spicyapi-com-agent-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-agent-tools-api-openapi.yml
- filename: spicyapi-com-audio-api-openapi.yml
  format: yaml
  label: spicyapi-com Audio API
  slug: spicyapi-com-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-audio-api-openapi.yml
- filename: spicyapi-com-characters-api-openapi.yml
  format: yaml
  label: spicyapi-com Characters API
  slug: spicyapi-com-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-characters-api-openapi.yml
- filename: spicyapi-com-core-api-openapi.yml
  format: yaml
  label: spicyapi-com Core API
  slug: spicyapi-com-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-core-api-openapi.yml
- filename: spicyapi-com-default-api-openapi.yml
  format: yaml
  label: spicyapi-com Default API
  slug: spicyapi-com-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-default-api-openapi.yml
- filename: spicyapi-com-embeddings-api-openapi.yml
  format: yaml
  label: spicyapi-com Embeddings API
  slug: spicyapi-com-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-embeddings-api-openapi.yml
- filename: spicyapi-com-guarded-api-openapi.yml
  format: yaml
  label: spicyapi-com Guarded API
  slug: spicyapi-com-guarded-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-guarded-api-openapi.yml
- filename: spicyapi-com-images-api-openapi.yml
  format: yaml
  label: spicyapi-com Images API
  slug: spicyapi-com-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-images-api-openapi.yml
- filename: spicyapi-com-live-calls-api-openapi.yml
  format: yaml
  label: spicyapi-com Live calls API
  slug: spicyapi-com-live-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-live-calls-api-openapi.yml
- filename: spicyapi-com-moderation-api-openapi.yml
  format: yaml
  label: spicyapi-com Moderation API
  slug: spicyapi-com-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-moderation-api-openapi.yml
- filename: spicyapi-com-video-api-openapi.yml
  format: yaml
  label: spicyapi-com Video API
  slug: spicyapi-com-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-video-api-openapi.yml
- filename: spicyapi-com-chat-completions-api-openapi.yml
  format: yaml
  label: spicyapi-com Chat Completions API
  slug: spicyapi-com-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi-com/openapi/spicyapi-com-chat-completions-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - KP
    - IR
    - SY
    - CU
    served: []
    text: You may not use our Services from countries subject to UK, US (OFAC), or EU sanctions, including North Korea, Iran, Syria, Cuba, and Crimea.
  entity_types:
  - text: Our services are intended for business and commercial use by developers, platforms, and applications serving adult content to verified adult users.
    type: business
  - text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to use our services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to use our services.
    value: '18'
  restricted_uses:
  - summary: Adult content for minors or young-looking people
    text: Any content depicting, suggesting, or appearing to depict minors or "young-looking" individuals
  - summary: Sanctioned jurisdictions and parties
    text: You represent that you are not on any sanctions list including SDN, UK HMT Consolidated List, or EU Consolidated List.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Where the law of your location requires it, you must complete a one-time age verification through our third-party provider before your account can generate or retrieve content
excluded_countries:
- KP
- IR
- SY
- CU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: spicyapi-com
provenance_date: '2026-11-10'
provider_name: spicyapi-com
provider_slug: spicyapi-com
slug: spicyapi-com-eligibility
source_date: '2026-11-10'
source_filename: spicyapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.spicyapi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: spicyapi-com\naid: spicyapi-com\nurl: https://www.spicyapi.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - KP\n  - IR\n  - SY\n  - CU\n  text: You may not use our Services from countries subject to UK, US (OFAC), or EU sanctions, including North Korea,\n    Iran, Syria, Cuba, and Crimea.\nentity_types:\n- type: business\n  text: Our services are intended for business and commercial use by developers, platforms, and applications serving\n    adult content to verified adult users.\n- type: individual\n  text: You must be at least 18 years of age (or the age of majority\
  \ in your jurisdiction) to use our services.\nrestricted_uses:\n- summary: Adult content for minors or young-looking people\n  text: Any content depicting, suggesting, or appearing to depict minors or \"young-looking\" individuals\n- summary: Sanctioned jurisdictions and parties\n  text: You represent that you are not on any sanctions list including SDN, UK HMT Consolidated List, or EU Consolidated\n    List.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Where the law of your location requires it, you must complete a one-time age verification through our third-party\n    provider before your account can generate or retrieve content\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to use our services.\n"
source_yaml_url: https://artifacts.apis.io/spicyapi-com/eligibility/spicyapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from spicyapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Adult
- Image Generation
- Video Generation
- Voice
---
