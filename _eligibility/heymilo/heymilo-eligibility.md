---
api_specs:
- filename: heymilo-ats-api-openapi.yml
  format: yaml
  label: HeyMilo ATS API
  slug: heymilo-ats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-ats-api-openapi.yml
- filename: heymilo-candidates-api-openapi.yml
  format: yaml
  label: HeyMilo Candidates API
  slug: heymilo-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-candidates-api-openapi.yml
- filename: heymilo-design-template-groups-api-openapi.yml
  format: yaml
  label: HeyMilo Design Template Groups API
  slug: heymilo-design-template-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-design-template-groups-api-openapi.yml
- filename: heymilo-design-templates-api-openapi.yml
  format: yaml
  label: HeyMilo Design Templates API
  slug: heymilo-design-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-design-templates-api-openapi.yml
- filename: heymilo-domains-api-openapi.yml
  format: yaml
  label: HeyMilo Domains API
  slug: heymilo-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-domains-api-openapi.yml
- filename: heymilo-email-template-groups-api-openapi.yml
  format: yaml
  label: HeyMilo Email Template Groups API
  slug: heymilo-email-template-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-email-template-groups-api-openapi.yml
- filename: heymilo-email-templates-api-openapi.yml
  format: yaml
  label: HeyMilo Email Templates API
  slug: heymilo-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-email-templates-api-openapi.yml
- filename: heymilo-health-api-openapi.yml
  format: yaml
  label: HeyMilo Health API
  slug: heymilo-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-health-api-openapi.yml
- filename: heymilo-interview-templates-api-openapi.yml
  format: yaml
  label: HeyMilo Interview Templates API
  slug: heymilo-interview-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-interview-templates-api-openapi.yml
- filename: heymilo-interviewers-api-openapi.yml
  format: yaml
  label: HeyMilo Interviewers API
  slug: heymilo-interviewers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-interviewers-api-openapi.yml
- filename: heymilo-interviews-api-openapi.yml
  format: yaml
  label: HeyMilo Interviews API
  slug: heymilo-interviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-interviews-api-openapi.yml
- filename: heymilo-phone-numbers-api-openapi.yml
  format: yaml
  label: HeyMilo Phone Numbers API
  slug: heymilo-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-phone-numbers-api-openapi.yml
- filename: heymilo-questions-api-openapi.yml
  format: yaml
  label: HeyMilo Questions API
  slug: heymilo-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-questions-api-openapi.yml
- filename: heymilo-schema-discovery-api-openapi.yml
  format: yaml
  label: HeyMilo Schema Discovery API
  slug: heymilo-schema-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-schema-discovery-api-openapi.yml
- filename: heymilo-sender-emails-api-openapi.yml
  format: yaml
  label: HeyMilo Sender Emails API
  slug: heymilo-sender-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-sender-emails-api-openapi.yml
- filename: heymilo-voices-api-openapi.yml
  format: yaml
  label: HeyMilo Voices API
  slug: heymilo-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-voices-api-openapi.yml
- filename: heymilo-webhooks-api-openapi.yml
  format: yaml
  label: HeyMilo Webhooks API
  slug: heymilo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-webhooks-api-openapi.yml
- filename: heymilo-workspaces-api-openapi.yml
  format: yaml
  label: HeyMilo Workspaces API
  slug: heymilo-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymilo/openapi/heymilo-workspaces-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Advertising or selling goods and services
    text: Use the Services to advertise or offer to sell goods and services.
  - summary: Creating accounts by automated means
    text: creating user accounts by automated means or under false pretenses
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
name: HeyMilo
provenance_date: '2026-11-09'
provider_name: HeyMilo
provider_slug: heymilo
slug: heymilo-eligibility
source_date: '2026-11-09'
source_filename: heymilo-eligibility.yml
source_heading: Eligibility
source_page: https://www.heymilo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HeyMilo\naid: heymilo\nurl: https://www.heymilo.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Advertising or selling goods and services\n  text: Use the Services to advertise or offer to sell goods and services.\n- summary: Creating accounts by automated means\n  text: creating user accounts by automated means or under false pretenses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/heymilo/eligibility/heymilo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from HeyMilo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recruiting
- Hiring
- Human Resources
- Artificial Intelligence
- AI Agents
- Interviewing
- Candidate Screening
- Voice AI
- Webhook
- ATS Integration
---
