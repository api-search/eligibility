---
api_specs:
- filename: pirsch-access-links-api-openapi.yml
  format: yaml
  label: Pirsch Access Links API
  slug: pirsch-access-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-access-links-api-openapi.yml
- filename: pirsch-authentication-api-openapi.yml
  format: yaml
  label: Pirsch Authentication API
  slug: pirsch-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-authentication-api-openapi.yml
- filename: pirsch-clients-api-openapi.yml
  format: yaml
  label: Pirsch Clients API
  slug: pirsch-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-clients-api-openapi.yml
- filename: pirsch-conversion-goals-api-openapi.yml
  format: yaml
  label: Pirsch Conversion Goals API
  slug: pirsch-conversion-goals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-conversion-goals-api-openapi.yml
- filename: pirsch-domains-api-openapi.yml
  format: yaml
  label: Pirsch Domains API
  slug: pirsch-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-domains-api-openapi.yml
- filename: pirsch-email-reports-api-openapi.yml
  format: yaml
  label: Pirsch Email Reports API
  slug: pirsch-email-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-email-reports-api-openapi.yml
- filename: pirsch-funnels-api-openapi.yml
  format: yaml
  label: Pirsch Funnels API
  slug: pirsch-funnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-funnels-api-openapi.yml
- filename: pirsch-members-api-openapi.yml
  format: yaml
  label: Pirsch Members API
  slug: pirsch-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-members-api-openapi.yml
- filename: pirsch-short-links-api-openapi.yml
  format: yaml
  label: Pirsch Short Links API
  slug: pirsch-short-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-short-links-api-openapi.yml
- filename: pirsch-statistics-api-openapi.yml
  format: yaml
  label: Pirsch Statistics API
  slug: pirsch-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-statistics-api-openapi.yml
- filename: pirsch-tracking-api-openapi.yml
  format: yaml
  label: Pirsch Tracking API
  slug: pirsch-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-tracking-api-openapi.yml
- filename: pirsch-traffic-management-api-openapi.yml
  format: yaml
  label: Pirsch Traffic Management API
  slug: pirsch-traffic-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-traffic-management-api-openapi.yml
- filename: pirsch-user-api-openapi.yml
  format: yaml
  label: Pirsch User API
  slug: pirsch-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-user-api-openapi.yml
- filename: pirsch-views-api-openapi.yml
  format: yaml
  label: Pirsch Views API
  slug: pirsch-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-views-api-openapi.yml
- filename: pirsch-webhooks-api-openapi.yml
  format: yaml
  label: Pirsch Webhooks API
  slug: pirsch-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pirsch/openapi/pirsch-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: There are no restrictions for Users in terms of being Consumers or Business Users;
    type: business
  - text: Users who are European Consumers are granted a statutory cancellation right under EU rules
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating laws or Terms
    text: violate laws, regulations and/or these Terms; infringe any third-party rights; considerably impair the Owner's legitimate interests; offend the Owner or any third party.
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
name: Pirsch
provenance_date: '2026-11-10'
provider_name: Pirsch
provider_slug: pirsch
slug: pirsch-eligibility
source_date: '2026-11-10'
source_filename: pirsch-eligibility.yml
source_heading: Eligibility
source_page: https://pirsch.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pirsch\naid: pirsch\nurl: https://pirsch.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: There are no restrictions for Users in terms of being Consumers or Business Users;\n- type: individual\n  text: Users who are European Consumers are granted a statutory cancellation right under EU rules\nrestricted_uses:\n- summary: Violating laws or Terms\n  text: violate laws, regulations and/or these Terms; infringe any third-party rights; considerably impair the Owner's\n    legitimate interests; offend the Owner or any third party.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pirsch/eligibility/pirsch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pirsch's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Privacy
- GDPR
- Cookie-Free
- Page Views
- Sessions
- Event
- Conversion Goals
- Funnels
- Traffic Sources
---
