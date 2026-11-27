---
api_specs:
- filename: anymailfinder-com-account-api-openapi.yml
  format: yaml
  label: Anymail Finder Account API
  slug: anymailfinder-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-account-api-openapi.yml
- filename: anymailfinder-com-bulk-api-openapi.yml
  format: yaml
  label: Anymail Finder Bulk API
  slug: anymailfinder-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-bulk-api-openapi.yml
- filename: anymailfinder-com-domain-api-openapi.yml
  format: yaml
  label: Anymail Finder Domain API
  slug: anymailfinder-com-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-domain-api-openapi.yml
- filename: anymailfinder-com-find-email-api-openapi.yml
  format: yaml
  label: Anymail Finder Find Email API
  slug: anymailfinder-com-find-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-find-email-api-openapi.yml
- filename: anymailfinder-com-geo-lead-api-openapi.yml
  format: yaml
  label: Anymail Finder Geo Lead API
  slug: anymailfinder-com-geo-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-geo-lead-api-openapi.yml
- filename: anymailfinder-com-report-api-openapi.yml
  format: yaml
  label: Anymail Finder Report API
  slug: anymailfinder-com-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-report-api-openapi.yml
- filename: anymailfinder-com-verify-email-api-openapi.yml
  format: yaml
  label: Anymail Finder Verify Email API
  slug: anymailfinder-com-verify-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-verify-email-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are provided to businesses only; by creating an account the Customer confirms that it is acting for purposes relating to its trade, business or profession and not as a consumer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Business-to-business communications only
    text: The Customer warrants that it will only use the Services for business-to-business communications.
  - summary: No unlawful spam
    text: The Customer shall not use the Services or Data to send, facilitate or enable spam or other communications that are unlawful under applicable electronic marketing, anti-spam or similar laws
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
name: Anymail Finder
provenance_date: '2026-11-09'
provider_name: Anymail Finder
provider_slug: anymailfinder-com
slug: anymailfinder-com-eligibility
source_date: '2026-11-09'
source_filename: anymailfinder-com-eligibility.yml
source_heading: Eligibility
source_page: https://anymailfinder.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anymail Finder\naid: anymailfinder-com\nurl: https://anymailfinder.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are provided to businesses only; by creating an account the Customer confirms that it is acting\n    for purposes relating to its trade, business or profession and not as a consumer.\nrestricted_uses:\n- summary: Business-to-business communications only\n  text: The Customer warrants that it will only use the Services for business-to-business communications.\n- summary: No unlawful\
  \ spam\n  text: The Customer shall not use the Services or Data to send, facilitate or enable spam or other communications\n    that are unlawful under applicable electronic marketing, anti-spam or similar laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anymailfinder-com/eligibility/anymailfinder-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Anymail Finder's own page on 2026-11-09.
synthetic: false
tags:
- Email Finder
- B2B
- Lead Generation
- Verification
---
