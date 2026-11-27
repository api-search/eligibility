---
api_specs:
- filename: adaptive-security-audit-logs-api-openapi.yml
  format: yaml
  label: Adaptive Security Audit Logs API
  slug: adaptive-security-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptive-security/openapi/adaptive-security-audit-logs-api-openapi.yml
- filename: adaptive-security-groups-api-openapi.yml
  format: yaml
  label: Adaptive Security Groups API
  slug: adaptive-security-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptive-security/openapi/adaptive-security-groups-api-openapi.yml
- filename: adaptive-security-phishing-api-openapi.yml
  format: yaml
  label: Adaptive Security Phishing API
  slug: adaptive-security-phishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptive-security/openapi/adaptive-security-phishing-api-openapi.yml
- filename: adaptive-security-training-api-openapi.yml
  format: yaml
  label: Adaptive Security Training API
  slug: adaptive-security-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptive-security/openapi/adaptive-security-training-api-openapi.yml
- filename: adaptive-security-users-api-openapi.yml
  format: yaml
  label: Adaptive Security Users API
  slug: adaptive-security-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptive-security/openapi/adaptive-security-users-api-openapi.yml
- filename: adaptive-security-email-security-api-openapi.yml
  format: yaml
  label: Adaptive Security Email Security API
  slug: adaptive-security-email-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptive-security/openapi/adaptive-security-email-security-api-openapi.yml
- filename: adaptive-security-webhooks-api-openapi.yml
  format: yaml
  label: Adaptive Security Webhooks API
  slug: adaptive-security-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptive-security/openapi/adaptive-security-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use our Services.
    value: '18'
  restricted_uses:
  - summary: Impersonation via simulated content
    text: You may not use simulated or AI-generated content to impersonate individuals outside of authorized training, testing, or educational scenarios, or in any manner that violates applicable law.
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
name: Adaptive Security
provenance_date: '2026-11-09'
provider_name: Adaptive Security
provider_slug: adaptive-security
slug: adaptive-security-eligibility
source_date: '2026-11-09'
source_filename: adaptive-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.adaptivesecurity.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adaptive Security\naid: adaptive-security\nurl: https://www.adaptivesecurity.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Impersonation via simulated content\n  text: You may not use simulated or AI-generated content to impersonate individuals outside of authorized training,\n    testing, or educational scenarios, or in any manner that violates applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/adaptive-security/eligibility/adaptive-security-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Adaptive Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Security Awareness Training
- Phishing Simulation
- Deepfake Defense
- AI Governance
- Social-Engineering
- Reporting
- Compliance
---
