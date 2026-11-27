---
api_specs:
- filename: semrush-hermes-partner-api-api-openapi.yml
  format: yaml
  label: Semrush Hermes Partner API
  slug: semrush-hermes-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semrush/openapi/semrush-hermes-partner-api-api-openapi.yml
- filename: semrush-jwt-issuer-api-openapi.yml
  format: yaml
  label: Semrush JWT Issuer API
  slug: semrush-jwt-issuer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semrush/openapi/semrush-jwt-issuer-api-openapi.yml
- filename: semrush-partner-service-api-openapi.yml
  format: yaml
  label: Semrush Partner Service API
  slug: semrush-partner-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/semrush/openapi/semrush-partner-service-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served: []
    text: The Semrush Items may not be downloaded or otherwise provided or made available, either directly or indirectly, (i) in Cuba, Iran, North Korea, Syria, Russia, Belarus, the Crimea region of Ukraine
  entity_types:
  - text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that you have the authority to bind such entity to this Agreement
    type: business
  - text: Each Account is intended and designed for use by an individual user, unless otherwise stated in your Subscription Plan.
    type: individual
  minimum_age:
    text: you are at least 18 years of age and have the capacity and authority to enter into this Agreement
    value: '18'
  restricted_uses:
  - summary: Sensitive information
    text: you agree not to use the Services to collect, manage or process sensitive information
  - summary: Military end-use
    text: nor will you use the Semrush Items for a military end-use or a military end-user in China, Russia or Venezuela
  - summary: Unlawful or abusive use
    text: use the Services for any purpose or in any manner that is unlawful
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
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Semrush
provenance_date: '2026-11-10'
provider_name: Semrush
provider_slug: semrush
slug: semrush-eligibility
source_date: '2026-11-10'
source_filename: semrush-eligibility.yml
source_heading: Eligibility
source_page: https://www.semrush.com/company/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Semrush\naid: semrush\nurl: https://www.semrush.com/company/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: The Semrush Items may not be downloaded or otherwise provided or made available, either directly or indirectly,\n    (i) in Cuba, Iran, North Korea, Syria, Russia, Belarus, the Crimea region of Ukraine\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a business or other legal entity, you represent that\n    you have the authority to bind such\
  \ entity to this Agreement\n- type: individual\n  text: Each Account is intended and designed for use by an individual user, unless otherwise stated in your Subscription\n    Plan.\nrestricted_uses:\n- summary: Sensitive information\n  text: you agree not to use the Services to collect, manage or process sensitive information\n- summary: Military end-use\n  text: nor will you use the Semrush Items for a military end-use or a military end-user in China, Russia or Venezuela\n- summary: Unlawful or abusive use\n  text: use the Services for any purpose or in any manner that is unlawful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age and have the capacity and authority to enter into this Agreement\n"
source_yaml_url: https://artifacts.apis.io/semrush/eligibility/semrush-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Semrush's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Search Engines
- SEO
- Marketing
- Marketing Intelligence
- Content Marketing
- Advertising
- Competitive Intelligence
- Keyword Research
- Backlinks
- Rank Tracking
- AI Search Visibility
- Local SEO
- MCP
---
