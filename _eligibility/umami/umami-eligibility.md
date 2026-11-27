---
api_specs:
- filename: umami-authentication-api-openapi.yml
  format: yaml
  label: Umami Authentication API
  slug: umami-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-authentication-api-openapi.yml
- filename: umami-teams-api-openapi.yml
  format: yaml
  label: Umami Teams API
  slug: umami-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-teams-api-openapi.yml
- filename: umami-users-api-openapi.yml
  format: yaml
  label: Umami Users API
  slug: umami-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-users-api-openapi.yml
- filename: umami-websites-api-openapi.yml
  format: yaml
  label: Umami Websites API
  slug: umami-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-websites-api-openapi.yml
- filename: umami-account-api-openapi.yml
  format: yaml
  label: Umami Account API
  slug: umami-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-account-api-openapi.yml
- filename: umami-administration-api-openapi.yml
  format: yaml
  label: Umami Administration API
  slug: umami-administration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-administration-api-openapi.yml
- filename: umami-boards-api-openapi.yml
  format: yaml
  label: Umami Boards API
  slug: umami-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-boards-api-openapi.yml
- filename: umami-collection-api-openapi.yml
  format: yaml
  label: Umami Collection API
  slug: umami-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-collection-api-openapi.yml
- filename: umami-dashboard-api-openapi.yml
  format: yaml
  label: Umami Dashboard API
  slug: umami-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-dashboard-api-openapi.yml
- filename: umami-links-api-openapi.yml
  format: yaml
  label: Umami Links API
  slug: umami-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-links-api-openapi.yml
- filename: umami-pixels-api-openapi.yml
  format: yaml
  label: Umami Pixels API
  slug: umami-pixels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-pixels-api-openapi.yml
- filename: umami-realtime-api-openapi.yml
  format: yaml
  label: Umami Realtime API
  slug: umami-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-realtime-api-openapi.yml
- filename: umami-scripts-api-openapi.yml
  format: yaml
  label: Umami Scripts API
  slug: umami-scripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-scripts-api-openapi.yml
- filename: umami-shares-api-openapi.yml
  format: yaml
  label: Umami Shares API
  slug: umami-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-shares-api-openapi.yml
- filename: umami-system-api-openapi.yml
  format: yaml
  label: Umami System API
  slug: umami-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-system-api-openapi.yml
- filename: umami-two-factor-authentication-api-openapi.yml
  format: yaml
  label: Umami Two-factor authentication API
  slug: umami-two-factor-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/umami/openapi/umami-two-factor-authentication-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity
    type: individual
  - text: on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Buying or purchasing agents
    text: Use a buying agent or purchasing agent to make purchases on the Services.
  - summary: Competing products
    text: Use the Services as part of any effort to build or offer a competing product or service.
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
name: Umami
provenance_date: '2026-11-10'
provider_name: Umami
provider_slug: umami
slug: umami-eligibility
source_date: '2026-11-10'
source_filename: umami-eligibility.yml
source_heading: Eligibility
source_page: https://umami.is/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Umami\naid: umami\nurl: https://umami.is/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not intended for distribution to or use by any person or entity in any jurisdiction or country where such\n    distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity\n- type: business\n  text: on behalf of an entity\nrestricted_uses:\n- summary: Buying or purchasing agents\n  text: Use a buying agent or purchasing agent to make purchases on the Services.\n- summary: Competing products\n  text: Use\
  \ the Services as part of any effort to build or offer a competing product or service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/umami/eligibility/umami-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Umami's own page on 2026-11-10.
synthetic: false
tags:
- Cookieless Tracking
- Open Source
- Privacy
- Web Analytics
- Website Analytics
- Product Analytics
- Event Tracking
- Self-Hosted
- GDPR
- Session Replay
- Heatmaps
- Marketing Attribution
---
