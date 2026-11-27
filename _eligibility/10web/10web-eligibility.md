---
api_specs:
- filename: 10web-account-api-openapi.yml
  format: yaml
  label: 10Web Account API
  slug: 10web-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-account-api-openapi.yml
- filename: 10web-backup-api-openapi.yml
  format: yaml
  label: 10Web Backup API
  slug: 10web-backup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-backup-api-openapi.yml
- filename: 10web-builder-api-openapi.yml
  format: yaml
  label: 10Web Builder API
  slug: 10web-builder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-builder-api-openapi.yml
- filename: 10web-cache-api-openapi.yml
  format: yaml
  label: 10Web Cache API
  slug: 10web-cache-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-cache-api-openapi.yml
- filename: 10web-certificate-api-openapi.yml
  format: yaml
  label: 10Web Certificate API
  slug: 10web-certificate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-certificate-api-openapi.yml
- filename: 10web-domain-api-openapi.yml
  format: yaml
  label: 10Web Domain API
  slug: 10web-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-domain-api-openapi.yml
- filename: 10web-php-management-api-openapi.yml
  format: yaml
  label: 10Web PHP Management API
  slug: 10web-php-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-php-management-api-openapi.yml
- filename: 10web-section-based-ai-api-openapi.yml
  format: yaml
  label: 10Web Section Based AI API
  slug: 10web-section-based-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-section-based-ai-api-openapi.yml
- filename: 10web-vibe-coding-api-openapi.yml
  format: yaml
  label: 10Web Vibe Coding API
  slug: 10web-vibe-coding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-vibe-coding-api-openapi.yml
- filename: 10web-website-api-openapi.yml
  format: yaml
  label: 10Web Website API
  slug: 10web-website-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-website-api-openapi.yml
- filename: 10web-wp-autologin-api-openapi.yml
  format: yaml
  label: 10Web WP Autologin API
  slug: 10web-wp-autologin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-wp-autologin-api-openapi.yml
- filename: 10web-zone-api-openapi.yml
  format: yaml
  label: 10Web Zone API
  slug: 10web-zone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-zone-api-openapi.yml
- filename: 10web-sub-domain-api-openapi.yml
  format: yaml
  label: 10Web Sub Domain API
  slug: 10web-sub-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/10web/openapi/10web-sub-domain-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You have to be of legal age of majority in the jurisdiction where you reside
    type: individual
  - text: be lawfully and duly organized under the requirements of respective laws in that jurisdiction
    type: business
  minimum_age:
    text: In case of minors (ages between 13 and the legal age of majority), have the permission of parents or legal guardians.
    value: legal age of majority
  restricted_uses:
  - summary: AI Builder recreation of third-party content
    text: You are not allowed to use AI Builder functionality, unless you have the right over the Content to be recreated with the use of AI Builder.
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
name: 10Web
provenance_date: '2026-11-09'
provider_name: 10Web
provider_slug: 10web
slug: 10web-eligibility
source_date: '2026-11-09'
source_filename: 10web-eligibility.yml
source_heading: Eligibility
source_page: https://10web.io/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 10Web\naid: 10web\nurl: https://10web.io/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You have to be of legal age of majority in the jurisdiction where you reside\n- type: business\n  text: be lawfully and duly organized under the requirements of respective laws in that jurisdiction\nrestricted_uses:\n- summary: AI Builder recreation of third-party content\n  text: You are not allowed to use AI Builder functionality, unless you have the right over the Content to be recreated\n    with the\
  \ use of AI Builder.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age of majority\n  text: In case of minors (ages between 13 and the legal age of majority), have the permission of parents or legal\n    guardians.\n"
source_yaml_url: https://artifacts.apis.io/10web/eligibility/10web-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 10Web's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Website Builder
- WordPress
- Hosting
- Website Generation
- No-Code
---
