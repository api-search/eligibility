---
api_specs:
- filename: availity-auth-attachments-api-openapi.yml
  format: yaml
  label: availity Auth Attachments API
  slug: availity-auth-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-auth-attachments-api-openapi.yml
- filename: availity-claim-attachments-api-openapi.yml
  format: yaml
  label: availity Claim Attachments API
  slug: availity-claim-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-claim-attachments-api-openapi.yml
- filename: availity-claim-status-api-openapi.yml
  format: yaml
  label: availity Claim Status API
  slug: availity-claim-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-claim-status-api-openapi.yml
- filename: availity-eligibility-api-openapi.yml
  format: yaml
  label: availity Eligibility API
  slug: availity-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-eligibility-api-openapi.yml
- filename: availity-enhanced-claim-status-api-openapi.yml
  format: yaml
  label: availity Enhanced Claim Status API
  slug: availity-enhanced-claim-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-enhanced-claim-status-api-openapi.yml
- filename: availity-is-auth-required-api-openapi.yml
  format: yaml
  label: availity Is Auth Required API
  slug: availity-is-auth-required-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-is-auth-required-api-openapi.yml
- filename: availity-service-reviews-api-openapi.yml
  format: yaml
  label: availity Service Reviews API
  slug: availity-service-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-service-reviews-api-openapi.yml
- filename: availity-availity-payer-list-api-openapi.yml
  format: yaml
  label: Availity Availity Payer List API
  slug: availity-availity-payer-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-availity-payer-list-api-openapi.yml
- filename: availity-claim-statuses-api-openapi.yml
  format: yaml
  label: Availity Claim Statuses API
  slug: availity-claim-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-claim-statuses-api-openapi.yml
- filename: availity-configurations-api-openapi.yml
  format: yaml
  label: Availity Configurations API
  slug: availity-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-configurations-api-openapi.yml
- filename: availity-coverages-api-openapi.yml
  format: yaml
  label: Availity Coverages API
  slug: availity-coverages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-coverages-api-openapi.yml
- filename: availity-dental-claims-api-openapi.yml
  format: yaml
  label: Availity Dental Claims API
  slug: availity-dental-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-dental-claims-api-openapi.yml
- filename: availity-dfs-api-openapi.yml
  format: yaml
  label: Availity Dfs API
  slug: availity-dfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-dfs-api-openapi.yml
- filename: availity-institutional-claims-api-openapi.yml
  format: yaml
  label: Availity Institutional Claims API
  slug: availity-institutional-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-institutional-claims-api-openapi.yml
- filename: availity-patient-cost-estimator-2-0-0-professional-api-openapi.yml
  format: yaml
  label: Availity Patient Cost Estimator 2.0.0 Professional API
  slug: availity-patient-cost-estimator-2-0-0-professional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-patient-cost-estimator-2-0-0-professional-api-openapi.yml
- filename: availity-professional-claims-api-openapi.yml
  format: yaml
  label: Availity Professional Claims API
  slug: availity-professional-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/availity/openapi/availity-professional-claims-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use this Site on behalf of an organization, such as a health provider, references in this Agreement to “you” and “your” are intended to be references to you individually and to your organization, both of which are to be bound.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical advice
    text: Availity is not authorized or licensed to provide, and does not engage in providing, medical advice.
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
name: Availity
provenance_date: '2026-11-09'
provider_name: Availity
provider_slug: availity
slug: availity-eligibility
source_date: '2026-11-09'
source_filename: availity-eligibility.yml
source_heading: Eligibility
source_page: https://www.availity.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Availity\naid: availity\nurl: https://www.availity.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use this Site on behalf of an organization, such as a health provider, references in this Agreement\n    to “you” and “your” are intended to be references to you individually and to your organization, both of which\n    are to be bound.\nrestricted_uses:\n- summary: No medical advice\n  text: Availity is not authorized or licensed to provide, and does not engage in providing, medical advice.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/availity/eligibility/availity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Availity's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Clearinghouse
- HIPAA
- X12 EDI
- Eligibility
- Claims
- Prior Authorization
- Revenue Cycle Management
- Payers
- Price Transparency
- Health Insurance
---
