---
api_specs:
- filename: hacware-admin-api-openapi.yml
  format: yaml
  label: Hacware Admin API
  slug: hacware-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-admin-api-openapi.yml
- filename: hacware-compliance-api-openapi.yml
  format: yaml
  label: Hacware Compliance API
  slug: hacware-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-compliance-api-openapi.yml
- filename: hacware-compliance-tenant-api-openapi.yml
  format: yaml
  label: Hacware Compliance-Tenant API
  slug: hacware-compliance-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-compliance-tenant-api-openapi.yml
- filename: hacware-customer-api-openapi.yml
  format: yaml
  label: Hacware Customer API
  slug: hacware-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-customer-api-openapi.yml
- filename: hacware-email-tenant-api-openapi.yml
  format: yaml
  label: Hacware Email-Tenant API
  slug: hacware-email-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-email-tenant-api-openapi.yml
- filename: hacware-group-api-openapi.yml
  format: yaml
  label: Hacware Group API
  slug: hacware-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-group-api-openapi.yml
- filename: hacware-multi-tenant-api-openapi.yml
  format: yaml
  label: Hacware Multi-Tenant API
  slug: hacware-multi-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-multi-tenant-api-openapi.yml
- filename: hacware-phishing-api-openapi.yml
  format: yaml
  label: Hacware Phishing API
  slug: hacware-phishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-phishing-api-openapi.yml
- filename: hacware-report-api-openapi.yml
  format: yaml
  label: Hacware Report API
  slug: hacware-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-report-api-openapi.yml
- filename: hacware-training-api-openapi.yml
  format: yaml
  label: Hacware Training API
  slug: hacware-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-training-api-openapi.yml
- filename: hacware-user-api-openapi.yml
  format: yaml
  label: Hacware User API
  slug: hacware-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-user-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
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
name: Hacware
provenance_date: '2026-11-09'
provider_name: Hacware
provider_slug: hacware
slug: hacware-eligibility
source_date: '2026-11-09'
source_filename: hacware-eligibility.yml
source_heading: Eligibility
source_page: https://hacware.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hacware\naid: hacware\nurl: https://hacware.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/hacware/eligibility/hacware-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Hacware's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Security Awareness
- Phishing
- Training
- Compliance
- Email Security
- Artificial Intelligence
---
