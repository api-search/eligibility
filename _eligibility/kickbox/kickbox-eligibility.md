---
api_specs:
- filename: kickbox-account-api-openapi.yml
  format: yaml
  label: Kickbox Account API
  slug: kickbox-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-account-api-openapi.yml
- filename: kickbox-batch-api-openapi.yml
  format: yaml
  label: Kickbox Batch API
  slug: kickbox-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-batch-api-openapi.yml
- filename: kickbox-open-api-openapi.yml
  format: yaml
  label: Kickbox Open API
  slug: kickbox-open-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-open-api-openapi.yml
- filename: kickbox-verification-api-openapi.yml
  format: yaml
  label: Kickbox Verification API
  slug: kickbox-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-verification-api-openapi.yml
- filename: kickbox-disposable-api-openapi.yml
  format: yaml
  label: Kickbox Disposable API
  slug: kickbox-disposable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kickbox/openapi/kickbox-disposable-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The arbitration section applies to customers with a billing address in the United States. No served or excluded countries are listed.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: Customer shall not use Kickbox to perform competitive analysis.
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
name: Kickbox
provenance_date: '2026-11-09'
provider_name: Kickbox
provider_slug: kickbox
slug: kickbox-eligibility
source_date: '2026-11-09'
source_filename: kickbox-eligibility.yml
source_heading: Eligibility
source_page: https://docs.kickbox.com/docs/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kickbox\naid: kickbox\nurl: https://docs.kickbox.com/docs/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The arbitration section applies to customers with a billing address in the United States. No served or excluded\n    countries are listed.\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Customer shall not use Kickbox to perform competitive analysis.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kickbox/eligibility/kickbox-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Kickbox's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Deliverability
- Data Quality
- Email
---
