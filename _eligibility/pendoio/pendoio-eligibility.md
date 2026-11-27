---
api_specs:
- filename: pendoio-account-api-openapi.yml
  format: yaml
  label: Pendo.io Account API
  slug: pendoio-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-account-api-openapi.yml
- filename: pendoio-admin-api-openapi.yml
  format: yaml
  label: Pendo.io Admin API
  slug: pendoio-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-admin-api-openapi.yml
- filename: pendoio-aggregation-api-openapi.yml
  format: yaml
  label: Pendo.io Aggregation API
  slug: pendoio-aggregation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-aggregation-api-openapi.yml
- filename: pendoio-bulk-deletion-gdpr-ccpa-api-openapi.yml
  format: yaml
  label: Pendo.io Bulk Deletion (GDPR/CCPA) API
  slug: pendoio-bulk-deletion-gdpr-ccpa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-bulk-deletion-gdpr-ccpa-api-openapi.yml
- filename: pendoio-conversations-api-openapi.yml
  format: yaml
  label: Pendo.io Conversations API
  slug: pendoio-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-conversations-api-openapi.yml
- filename: pendoio-data-sync-api-openapi.yml
  format: yaml
  label: Pendo.io Data Sync API
  slug: pendoio-data-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-data-sync-api-openapi.yml
- filename: pendoio-exclude-lists-servers-api-openapi.yml
  format: yaml
  label: Pendo.io Exclude Lists & Servers API
  slug: pendoio-exclude-lists-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-exclude-lists-servers-api-openapi.yml
- filename: pendoio-feature-api-openapi.yml
  format: yaml
  label: Pendo.io Feature API
  slug: pendoio-feature-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-feature-api-openapi.yml
- filename: pendoio-guide-api-openapi.yml
  format: yaml
  label: Pendo.io Guide API
  slug: pendoio-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-guide-api-openapi.yml
- filename: pendoio-listen-api-openapi.yml
  format: yaml
  label: Pendo.io Listen API
  slug: pendoio-listen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-listen-api-openapi.yml
- filename: pendoio-metadata-api-openapi.yml
  format: yaml
  label: Pendo.io Metadata API
  slug: pendoio-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-metadata-api-openapi.yml
- filename: pendoio-page-api-openapi.yml
  format: yaml
  label: Pendo.io Page API
  slug: pendoio-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-page-api-openapi.yml
- filename: pendoio-report-api-openapi.yml
  format: yaml
  label: Pendo.io Report API
  slug: pendoio-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-report-api-openapi.yml
- filename: pendoio-segment-api-openapi.yml
  format: yaml
  label: Pendo.io Segment API
  slug: pendoio-segment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-segment-api-openapi.yml
- filename: pendoio-track-api-openapi.yml
  format: yaml
  label: Pendo.io Track API
  slug: pendoio-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-track-api-openapi.yml
- filename: pendoio-visitor-api-openapi.yml
  format: yaml
  label: Pendo.io Visitor API
  slug: pendoio-visitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pendoio/openapi/pendoio-visitor-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use is not authorized in any jurisdiction that does not give effect to all provisions of the Terms of Use
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old, who are acting for themselves
    type: individual
  - text: or in their capacity as an employee or representative of a business entity or other organization
    type: business
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited purposes
    text: You promise not to use the Service for any purpose that is unlawful or prohibited by the Terms of Use, or any other purpose not reasonably intended by Pendo
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
name: Pendo.io
provenance_date: '2026-11-10'
provider_name: Pendo.io
provider_slug: pendoio
slug: pendoio-eligibility
source_date: '2026-11-10'
source_filename: pendoio-eligibility.yml
source_heading: Eligibility
source_page: https://www.pendo.io/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pendo.io\naid: pendoio\nurl: https://www.pendo.io/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use is not authorized in any jurisdiction that does not give effect to all provisions of the Terms of Use\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old, who are acting for themselves\n- type: business\n  text: or in their capacity as an employee or representative of a business entity or other organization\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: You promise not to\
  \ use the Service for any purpose that is unlawful or prohibited by the Terms of Use, or\n    any other purpose not reasonably intended by Pendo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/pendoio/eligibility/pendoio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pendo.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Analytics
- Product Experience
- Digital Adoption
- User Analytics
- In-App Guidance
- Customer Feedback
- Software-as-a-Service
---
