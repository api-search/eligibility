---
api_specs:
- filename: teambridge-collections-unified-api-api-openapi.yml
  format: yaml
  label: Teambridge Collections (Unified API) API
  slug: teambridge-collections-unified-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teambridge/openapi/teambridge-collections-unified-api-api-openapi.yml
- filename: teambridge-documents-api-openapi.yml
  format: yaml
  label: Teambridge Documents API
  slug: teambridge-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teambridge/openapi/teambridge-documents-api-openapi.yml
- filename: teambridge-mappings-api-openapi.yml
  format: yaml
  label: Teambridge Mappings API
  slug: teambridge-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teambridge/openapi/teambridge-mappings-api-openapi.yml
- filename: teambridge-utilities-api-openapi.yml
  format: yaml
  label: Teambridge Utilities API
  slug: teambridge-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teambridge/openapi/teambridge-utilities-api-openapi.yml
- filename: teambridge-teambridge-external-api-api-openapi.yml
  format: yaml
  label: Teambridge External API
  slug: teambridge-teambridge-external-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teambridge/openapi/teambridge-teambridge-external-api-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Site for use only by persons located in the United States.
  entity_types:
  - text: This Site is offered and available to Users and Guests who are 18 years of age or older and reside in the United States.
    type: individual
  - text: '"Customer" means a business customer who has contracted with Teambridge, directly or indirectly, for use of the Site for the Services.'
    type: business
  minimum_age:
    text: This Site is offered and available to Users and Guests who are 18 years of age or older and reside in the United States.
    value: '18'
  restricted_uses:
  - summary: Affiliate referrals of own business or duplicates
    text: Existing customers, leads already recorded by Teambridge, duplicate referrals, referrals of the affiliate's own business and fraudulent or artificially created accounts are not eligible.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Affiliates must be approved by Teambridge before using a referral link.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Teambridge
provenance_date: '2026-11-10'
provider_name: Teambridge
provider_slug: teambridge
slug: teambridge-eligibility
source_date: '2026-11-10'
source_filename: teambridge-eligibility.yml
source_heading: Eligibility
source_page: https://www.teambridge.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Teambridge\naid: teambridge\nurl: https://www.teambridge.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Site for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Site is offered and available to Users and Guests who are 18 years of age or older and reside in the\n    United States.\n- type: business\n  text: '\"Customer\" means a business customer who has contracted with Teambridge, directly or indirectly, for use\n    of the Site for the Services.'\nrestricted_uses:\n- summary: Affiliate referrals\
  \ of own business or duplicates\n  text: Existing customers, leads already recorded by Teambridge, duplicate referrals, referrals of the affiliate's\n    own business and fraudulent or artificially created accounts are not eligible.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Affiliates must be approved by Teambridge before using a referral link.\nminimum_age:\n  value: '18'\n  text: This Site is offered and available to Users and Guests who are 18 years of age or older and reside in the\n    United States.\n"
source_yaml_url: https://artifacts.apis.io/teambridge/eligibility/teambridge-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Teambridge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Workforce Management
- Scheduling
- Time Tracking
- Payroll
- Human Resources
- Frontline
- Webhook
---
