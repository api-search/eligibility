---
api_specs:
- filename: worklittle-job-boards-api-openapi.yml
  format: yaml
  label: Worklittle Job Boards API
  slug: worklittle-job-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-job-boards-api-openapi.yml
- filename: worklittle-jobs-api-openapi.yml
  format: yaml
  label: Worklittle Jobs API
  slug: worklittle-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-jobs-api-openapi.yml
- filename: worklittle-agent-documents-api-openapi.yml
  format: yaml
  label: Worklittle Agent Documents API
  slug: worklittle-agent-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-agent-documents-api-openapi.yml
- filename: worklittle-apply-api-openapi.yml
  format: yaml
  label: Worklittle Apply API
  slug: worklittle-apply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-apply-api-openapi.yml
- filename: worklittle-attendance-api-openapi.yml
  format: yaml
  label: Worklittle Attendance API
  slug: worklittle-attendance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-attendance-api-openapi.yml
- filename: worklittle-billing-api-openapi.yml
  format: yaml
  label: Worklittle Billing API
  slug: worklittle-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-billing-api-openapi.yml
- filename: worklittle-candidates-api-openapi.yml
  format: yaml
  label: Worklittle Candidates API
  slug: worklittle-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-candidates-api-openapi.yml
- filename: worklittle-documents-api-openapi.yml
  format: yaml
  label: Worklittle Documents API
  slug: worklittle-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-documents-api-openapi.yml
- filename: worklittle-email-offers-api-openapi.yml
  format: yaml
  label: Worklittle Email Offers API
  slug: worklittle-email-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-email-offers-api-openapi.yml
- filename: worklittle-employees-api-openapi.yml
  format: yaml
  label: Worklittle Employees API
  slug: worklittle-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-employees-api-openapi.yml
- filename: worklittle-employer-jobs-api-openapi.yml
  format: yaml
  label: Worklittle Employer Jobs API
  slug: worklittle-employer-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-employer-jobs-api-openapi.yml
- filename: worklittle-job-listings-api-openapi.yml
  format: yaml
  label: Worklittle Job Listings API
  slug: worklittle-job-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-job-listings-api-openapi.yml
- filename: worklittle-organization-api-openapi.yml
  format: yaml
  label: Worklittle Organization API
  slug: worklittle-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-organization-api-openapi.yml
- filename: worklittle-surveys-api-openapi.yml
  format: yaml
  label: Worklittle Surveys API
  slug: worklittle-surveys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-surveys-api-openapi.yml
- filename: worklittle-webhooks-api-openapi.yml
  format: yaml
  label: Worklittle Webhooks API
  slug: worklittle-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-webhooks-api-openapi.yml
- filename: worklittle-people-api-openapi.yml
  format: yaml
  label: Worklittle People API
  slug: worklittle-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/worklittle/openapi/worklittle-people-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or ordinarily resident in, a country or region subject to comprehensive U.S. sanctions, or if you appear on a U.S. government restricted party list.
  entity_types:
  - text: You must be at least 13 years old to use the Services.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Services.
    value: '13'
  restricted_uses:
  - summary: Impersonation via AI
    text: Use AI features to create content that impersonates a real person, fabricates credentials or references, or misleads an employer or candidate.
  - summary: Protected-characteristic screening
    text: You must not use the Services to screen people using characteristics protected by law, or to build a proxy for those characteristics.
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
name: Worklittle
provenance_date: '2026-11-10'
provider_name: Worklittle
provider_slug: worklittle
slug: worklittle-eligibility
source_date: '2026-11-10'
source_filename: worklittle-eligibility.yml
source_heading: Eligibility
source_page: https://worklittle.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Worklittle\naid: worklittle\nurl: https://worklittle.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or ordinarily resident in, a country or region subject\n    to comprehensive U.S. sanctions, or if you appear on a U.S. government restricted party list.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Services.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\n\
  restricted_uses:\n- summary: Impersonation via AI\n  text: Use AI features to create content that impersonates a real person, fabricates credentials or references,\n    or misleads an employer or candidate.\n- summary: Protected-characteristic screening\n  text: You must not use the Services to screen people using characteristics protected by law, or to build a proxy\n    for those characteristics.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/worklittle/eligibility/worklittle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Worklittle's own page on 2026-11-10.
synthetic: false
tags:
- Job Search
- Applicant Tracking
- Recruiting
- Workforce Intelligence
- Job Board
- Webhook
- MCP
---
